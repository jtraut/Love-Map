# Love Map

A single-page tool for working through the Gottman **Love Maps** exercises from *The Seven Principles for Making Marriage Work* by John M. Gottman, PhD & Nan Silver.

## What's included

- **Love Maps Questionnaire** — 20 true/false questions that score your current knowledge of each other's inner world
- **Exercise 1: The 20 Questions Game** — a randomized, point-scored game drawn from 60 questions; play together out loud
- **Exercise 2: Open-Ended Questions** — 30 conversation-starter questions to explore with your partner
- **Exercise 3: Who Am I?** — five sections of deep self-reflection prompts with write-in text areas

## How to use

No server, no install, no account. Open it one of two ways:

**Online (GitHub Pages):** [jtraut.github.io/Love-Map](https://jtraut.github.io/Love-Map/)

**Locally:** download `love_map.html` and open it in any modern browser — no internet connection needed.

Everything runs locally in your browser. Your questionnaire answers and Exercise 3 responses are **automatically saved to your browser's localStorage** — they'll still be there if you close and reopen the tab, as long as you use the same browser on the same device.

To back up your responses or move them to another device, use the **⬇ Export** button in the top bar to download a `love_map_responses_<date>.json` file. Use **⬆ Import** to restore from that file. Exported JSON files are gitignored so they won't be committed if you save them inside this project folder.

## Using this for yourself (without publishing your answers)

The exercises in this tool — especially Exercise 3 — involve personal reflections you probably don't want in a public git history. To use this privately:

1. **Download the file** — click *Code → Download ZIP* on GitHub, or save `love_map.html` directly to your computer.
2. **Open it locally** — double-click the file or drag it into your browser. No internet connection needed after that.
3. **Don't fork and commit answers** — if you fork this repo and fill in the text areas, those answers won't be committed automatically (the file itself doesn't change). But if you save the HTML file after editing it in a text editor with your answers inside, and then push that, they'd be public. Just keep your copy local.

If you want to customize the questions or styling for your own relationship, fork the repo, make your changes, and keep your fork private (GitHub lets you change visibility under *Settings → Danger Zone*).

## Attribution

All exercises and questions are from *The Seven Principles for Making Marriage Work* by John M. Gottman, PhD & Nan Silver. This is a personal, non-commercial project created to make these exercises more accessible. Please support the authors by [purchasing the book](https://www.gottman.com/product/the-seven-principles-for-making-marriage-work/).

## Contributing

Bug fixes and improvements to the questions, layout, or accessibility are welcome via pull request. Please don't submit PRs that include personal answers or relationship-specific content.
