# Candidates — The Word You'd Delete From the Dictionary

Judge criteria (from the competition's judge brief, most important first):
1. Names one real word a reader recognises, to erase forever.
2. Funny at first sight — the joke lands the moment the word is gone, no caption needed.
3. The humour comes from the word itself — its sound, double meanings, or the gap it would leave — not from shock alone.
4. Fresh — a word the rest of the field would not think of first, still instantly understood.
5. Exact — one word, spelled correctly, nothing added around it.

Scored 1–5 per criterion, 25 max. All eight words are my own original picks.

## 1. moist — 19/25
- Real word: 5 — universally recognised.
- Instant funny: 4 — the famous "moist" disgust meme lands immediately.
- From the word itself: 4 — the sound of the word is the joke.
- Fresh: 1 — the single most obvious pick; the field will be full of it.
- Exact: 5 — one word, correctly spelled.
- Reason: strong joke, killed by freshness — everyone thinks of it first.

## 2. colonel — 23/25 ⭐ PICK
- Real word: 5 — universally recognised.
- Instant funny: 4 — the moment it is gone, nobody ever has to explain again why it is pronounced "kernel".
- From the word itself: 5 — the joke is the word's own spelling-versus-sound mismatch; the gap it leaves is a language that finally makes sense.
- Fresh: 4 — a spelling-pronunciation pick, not the field's first thought.
- Exact: 5 — one word, correctly spelled.
- Reason: the funniest deletion is one that fixes the language — erasing "colonel" deletes the most famous lie in English spelling.

## 3. defenestration — 22/25
- Real word: 4 — recognised, but less common than the others.
- Instant funny: 3 — the gap joke (no word left for throwing someone out of a window) needs a beat to land.
- From the word itself: 5 — the word is funny to say and its absence leaves a hole nothing else fills.
- Fresh: 5 — almost nobody's first pick.
- Exact: 5 — one word, correctly spelled.
- Reason: delightful and fresh, but the joke arrives a half-second slower than the winner's.

## 4. synergy — 19/25
- Real word: 5 — universally recognised.
- Instant funny: 3 — office workers smile; the joke is about corporate culture, not the word.
- From the word itself: 3 — the humour comes from the meetings it haunts, not the word's sound or meaning.
- Fresh: 3 — a common jargon pick.
- Exact: 5 — one word, correctly spelled.
- Reason: a satisfying deletion, but the joke lives outside the word.

## 5. kerfuffle — 20/25
- Real word: 4 — widely recognised, slightly old-fashioned.
- Instant funny: 3 — funny to say, but deleting it removes a charming word, which is sad as much as funny.
- From the word itself: 4 — its bouncy sound is the joke.
- Fresh: 4 — not a first pick for most of the field.
- Exact: 5 — one word, correctly spelled.
- Reason: fun to say, but erasing a delightful word feels like a loss, not a punchline.

## 6. discombobulate — 20/25
- Real word: 5 — universally recognised.
- Instant funny: 3 — the self-referential joke (deleting the word for confusion would itself discombobulate) is clever, not instant.
- From the word itself: 4 — the word describes its own deletion.
- Fresh: 3 — a known "funny word" list regular.
- Exact: 5 — one word, correctly spelled.
- Reason: clever and self-referential, but it reads as a riddle rather than a punchline.

## 7. queue — 22/25
- Real word: 5 — universally recognised.
- Instant funny: 4 — one letter plus four silent letters standing in line; deleting it dismisses the queue.
- From the word itself: 5 — the spelling is the joke.
- Fresh: 3 — the "four silent letters" observation is a well-known meme.
- Exact: 5 — one word, correctly spelled.
- Reason: nearly as strong as the pick, but the joke is already a familiar internet observation.

## 8. Worcestershire — 19/25
- Real word: 4 — recognised as the sauce, but a proper noun more than a dictionary word.
- Instant funny: 3 — everyone who has ever tried to say or spell it nods.
- From the word itself: 4 — its unpronounceable spelling is the joke.
- Fresh: 4 — an unusual pick.
- Exact: 4 — proper-noun status and capitalisation make it a weaker "dictionary word" than the others.
- Reason: the same spelling joke as the winner, but weaker — it is a place/sauce name, not a word of the language.

## Pick
**colonel** (23/25) — the highest score. It beats "moist" on freshness, "defenestration" and
"queue" on how fast the joke lands, and every rival on humour that comes from the word itself:
the word is spelled nothing like it sounds, and erasing it is the only edit that makes English
honest.

## Revision (before / after)
- Before (first draft of `main.py`): the program wrote the word followed by a trailing newline
  (`"colonel\n"`). Re-reading the judge brief, criterion 5 demands the entry be exact — one word,
  "with nothing added around it". A trailing newline is an extra character the judge never asked for.
- After (revised `main.py`): the program writes exactly `colonel` — seven characters, no trailing
  newline, no whitespace — and asserts the output is a single word before writing. The pick itself
  survived the revision: re-scoring the runner-up "queue" against "colonel" after the first draft
  confirmed "colonel" still leads (23 vs 22), so the revision changed the program's output handling,
  not the word.
