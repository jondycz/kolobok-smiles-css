# KOLOBOK Smiles CSS

An unofficial CSS library that wraps the [KOLOBOK Smiles](http://www.en.kolobok.us) emoticons into easy-to-use CSS classes. Simply include the stylesheet and add class names to display animated smileys in your web pages.

> **Disclaimer:** This project is not affiliated with or endorsed by the original author. It is a community-made CSS wrapper for convenience. All artwork remains the property of its original creator.

## Installation

Download the [latest release](../../releases/latest) zip, or include the files directly:

```html
<link rel="stylesheet" href="kolobok.min.css">
```

## Usage

Use a `<span>` (or any inline element) with the base class `kolobok` and the smile name:

```html
<span class="kolobok dance"></span>
<span class="kolobok kiss"></span>
<span class="kolobok rofl"></span>
<span class="kolobok girl_in_love"></span>
```

## Available Categories

| Category | Examples |
|----------|----------|
| Standard | `acute`, `dance`, `kiss`, `rofl`, `good`, `sad` |
| Sport | `aikido`, `nhl`, `fans`, `training1` |
| RPG | `assassin`, `wizard`, `vampire`, `king` |
| Remake | `biggrin`, `cool`, `crazy`, `lol`, `wink` |
| Personal | `angel`, `neo`, `santa`, `superman`, `pooh` |
| Other | `bomb`, `heart`, `skull`, `spam` |
| Madhouse | `alcoholic`, `gamer1`, `pilot`, `prankster` |
| He & She | `flirt`, `girl_dance`, `give_rose`, `kiss2` |

Browse all smiles on the [demo website](../../deployments).

## Building from Source

```bash
npm install
npm run build
```

This compiles `kolobok.scss` into `kolobok.css` and `kolobok.min.css`.

## Project Structure

```
├── kolobok.scss          # Source SCSS
├── index.html            # Demo/browse website
├── KOLOBOK/              # Original smile GIF images
│   ├── aiwan_smiles/     # Categorized smile images
│   ├── Copyright_en.txt  # English license
│   └── Copyright_ru.txt  # Russian license
├── package.json          # Build configuration
└── .github/workflows/    # CI: build, deploy to Pages, publish release
```

## Credits & License

**All artwork is created by and remains the sole property of Mantsurov Ivan (Aiwan) © 2004–2010.**

- Original project: [http://www.en.kolobok.us](http://www.en.kolobok.us)
- License: [KOLOBOK/Copyright_en.txt](KOLOBOK/Copyright_en.txt)

The smiles are free for personal, non-commercial use. Commercial use requires permission from the original author. See the full license file for complete terms.

The CSS wrapper code in this repository (the `.scss` file and build tooling) is provided as-is for community convenience.
