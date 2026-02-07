# Flint — Idea Spark

Strike two notes together. Write what the collision reveals.

Flint picks two random notes from your vault, places them side by side, and asks: *what does this combination make you think?* If something sparks, write it down and save it as a new note. If nothing clicks, skip and try another pair.

Over time you build a web of original ideas born from juxtaposition — connections you'd never have made browsing your vault sequentially.

## How it works

1. **Open Flint** — Command palette (`Flint: Strike two notes`) or the flame icon in the ribbon
2. **Read the pair** — Two random notes displayed side by side
3. **Shuffle or pick** — Replace either note with another random pick, or search for a specific one
4. **Write the spark** — What does the collision make you think? Type your idea in the text area
5. **Save** — Creates a new note with your spark and backlinks to both source notes

Saved sparks look like this:

```markdown
Your original idea goes here.

---

## Sparked from

- [[Note A]]
- [[Note B]]
```

## Features

- **Weighted randomness** — Optionally favors notes with fewer connections (orphans are dormant potential)
- **Session memory** — Won't repeat notes you've already seen until the pool is exhausted
- **Folder scoping** — Draw from a specific folder, save sparks to another
- **Keyboard shortcut** — `Cmd/Ctrl+Enter` to save without leaving the keyboard
- **Clickable notifications** — After saving, click the notice to jump to your new spark
- **Resizable dialog** — Drag the corner to make the modal wider or taller

## Settings

- **Source folder** — Which notes to draw from (default: entire vault)
- **Output folder** — Where new spark notes are saved (default: vault root)
- **Prefer orphan notes** — Weight selection toward less-connected notes

## Install

### From Community Plugins

1. Open **Settings > Community Plugins** in Obsidian
2. Search for **Flint**
3. Click **Install**, then **Enable**

### Manual

1. Download `main.js`, `manifest.json`, and `styles.css` from the [latest release](https://github.com/MaggieMcgu/obsidian-flint/releases)
2. Create a folder called `flint` in your vault's `.obsidian/plugins/` directory
3. Copy the three files into it
4. Enable the plugin in **Settings > Community Plugins**

## Why "Flint"?

Flint is a sister plugin to [Cairn](https://github.com/MaggieMcgu/obsidian-cairn) (an essay composer). Both are rocks. Cairn builds structure from existing notes. Flint strikes two ideas together to create something new.

## Support

Flint is free and open source. If it sparks something good, tips are welcome on [Venmo](https://venmo.com/KiKiBouba).

## License

[MIT](LICENSE)
