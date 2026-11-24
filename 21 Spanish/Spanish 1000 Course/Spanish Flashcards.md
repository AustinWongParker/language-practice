# 🗂 Spanish Flashcards

Your flashcards are built into Obsidian: a small in-house plugin called **Spanish Flashcards**. It works like Anki, using spaced repetition to show each word just before you'd forget it, but it's tied to the [[Spanish 1000 Course]].

## Open it
- Click the **layers** icon (three stacked sheets) in the left sidebar, or
- click the card count (**🗂 12 cards**) in the bottom status bar, or
- press `Ctrl+P` and run **Spanish Flashcards: Study**.

## How a card works
1. You see the Spanish word and a short phrase, and hear it read aloud.
2. Say what it means out loud, then press **Show answer** (or `Space`).
3. Grade yourself honestly:

| Button | Key | When | What happens |
|---|---|---|---|
| **Again** | `1` | You didn't know it | Comes back in a few cards, and again tomorrow |
| **Hard** | `2` | You got it, with effort | Comes back a little later than last time |
| **Good** | `3` or `Space` | You knew it | Comes back later: 1 day, then about 3, 8, 20 days... |
| **Easy** | `4` | Instant, effortless | Jumps further ahead |

Press `R` or 🔊 to hear the card again. Each button shows when you'll see the card next. Click **Lesson 12 · #108** on the back of a card to open the lesson that teaches it.

## How it stays in step with your lessons
- **New words unlock when you reach their lesson.** Open today's lesson and its 10 words are waiting; finish the lesson, and tomorrow's unlock with the next one.
- **Review days have no new words**, so you'll only get reviews.
- **Miss a day?** New words wait for you, and your reviews are still there, oldest first.
- Reviews always come before new cards, so the important ones get done first.

## Your own cards
Add any word or phrase to [[My Flashcards]], one per line, as `Spanish :: English`:

```
- la playa :: the beach
- ¿Me lo puedes repetir? :: Can you repeat it for me?
```

They show up as new cards right away, after any course words.

## Settings
**Settings → Community plugins → Spanish Flashcards** (the ⚙️):
- **New cards per day:** the most new cards in one day (default 20). Lower it if reviews pile up.
- **Card direction:** Spanish → English (understanding), English → Spanish (speaking), or both (twice as many cards).
- **Read cards aloud** and **voice accent** (Mexico, US, Spain). Voices come from your device. On Windows, add one under **Settings → Time & language → Speech → Add voices** if you hear nothing.

## Where your progress lives
Progress is saved in `flashcards-progress.tsv` in this folder (one line per card), so Obsidian Git syncs it between computers like any note. Obsidian hides `.tsv` files, so you won't see it in the sidebar. Avoid studying on two computers at the same time, or the two copies may conflict.

> [!info]- Prefer the real Anki app?
> `Spanish 1000 - Anki import.txt` in this folder is still a complete 1000-card Anki deck (File → Import in Anki, deck "Spanish 1000", note type Basic). Use one system or the other, not both.
