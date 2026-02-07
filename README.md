# Flint — Idea Spark

Strike two notes together. Write what the collision reveals.

I built Flint because I had hundreds of notes and no idea what they meant together. I'd browse my vault and see the same familiar paths every time. Flint fixes that by picking two notes at random, putting them side by side, and asking: *what does this combination make you think?*

Sometimes nothing. Skip, shuffle, try again. But sometimes two notes that have no business being next to each other produce an idea that neither one contains alone. That's the spark. You write it down, it becomes a new note, and it links back to its parents.

This is basically the first thing I've ever coded. It's simple and it's fun and I use it all the time.

## How it works

1. **Open Flint** — Command palette (`Flint: Strike two notes`) or the flame icon in the ribbon
2. **Read the pair** — Two random notes side by side
3. **Shuffle or pick** — Swap either note for a new random one, or search for something specific
4. **Write the spark** — Type the idea the collision gave you
5. **Save** — New note with backlinks to both parents

Saved sparks look like this:

```markdown
Your original idea goes here.

---

## Sparked from

- [[Note A]]
- [[Note B]]
```

## The orphan thing

Flint can weight its randomness toward notes with fewer connections — the ones you haven't linked to much, the ones gathering dust. Turns out those are often the most surprising ones to collide. Your most neglected notes might be your best material. Toggle this in settings.

## Other details

- Won't repeat notes you've already seen (resets when it runs out)
- Scope to a specific folder if you want, or let it roam the whole vault
- `Cmd/Ctrl+Enter` to save without reaching for the mouse
- Click the notification after saving to jump straight to your new note
- Drag the corner to resize the dialog

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

Sister plugin to [Cairn](https://github.com/MaggieMcgu/obsidian-cairn), an essay composer — that one's the more complicated work-in-progress. Both are rocks. Cairn stacks notes into structure. Flint strikes them together to see what catches fire.

I'd love to hear how you use it, what's broken, or what would make it better. Open an [issue](https://github.com/MaggieMcgu/obsidian-flint/issues) or find me at [moabsunnews.com](https://moabsunnews.com).

## Support

Flint is free and open source. If it sparks something good, tips are welcome on [Venmo](https://venmo.com/KiKiBouba).

## License

[MIT](LICENSE)
