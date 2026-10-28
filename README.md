# Dark Magician Trainer

A personal practice app for a Yu-Gi-Oh! Master Duel Dark Magician deck (40 main, 8 Extra).

- **Watch**: three combo lines played out on a duel field, step by step.
- **Practice**: pick the best next move; after each correct answer, read why, then tap Next move.
- **Play**: a free-play table with the real rules checked (Normal Summon, Tributes, costs, once-per-turn,
  Fusion, Ritual and Link Summons, Dark Magician of Destruction's own summon, Eternal Soul, Gaze of Timaeus).
- **Deck**: every card with its text and a "How to play it" coach.
- **Styles**: the popular ways to play the deck, with key cards and links into Watch and Practice.

Card text is built into the app. Card pictures load from the YGOPRODeck image server and are cached on the device.

## Updating
Upload the changed files to the repository (Add file → Upload files → Commit). Every release bumps the cache key in `sw.js`.
