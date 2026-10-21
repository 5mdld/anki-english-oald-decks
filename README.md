# 【egg rolls】Anki English Vocabulary Deck — Oxford 5k CEFR Core + COCA 20k Expansion | 中文翻译・日本語訳

An English vocabulary deck for Anki, combining Oxford CEFR A1–C1 core vocabulary with COCA 20k expansion vocabulary. Study one meaning per card with British and American pronunciation audio, example sentences, and optional Chinese and Japanese translations.

| [Download from GitHub →](https://github.com/5mdld/anki-english-oald-decks/releases) | [Download from AnkiWeb →](https://ankiweb.net/shared/info/1383468581) |
| :--- | :--- |
| Choose with or without example recordings. | Word audio included; no example recordings. |

## Overview

| Section | Headwords | Cards |
| --- | --- | --- |
| Oxford CEFR core, A1–C1 | ~4k | ~11k |
| COCA 20k expansion | ~15k | ~31k |
| Combined | ~16k unique headwords | ~42k |

Headword counts overlap: a word can have core meanings and additional meanings in the expansion. Each meaning appears in only one subdeck.

### Data sources

- CEFR levels come from the Oxford Advanced Learner’s Dictionary (OALD).
- Word-frequency rankings come from the Corpus of Contemporary American English (COCA).
- Only individual text items explicitly labeled `[AI]` are AI-generated. These include some Japanese definitions and some Japanese or Chinese example translations. All unmarked definitions and translations come from OALD.
- Only audio with an `AI` badge on its speaker icon is AI-generated; all other audio comes from OALD.

All other dictionary data comes from OALD.

## Deck structure

```text
eggrolls-OALD-20k
├── 01-CEFR
│   ├── A1
│   ├── A2
│   ├── B1
│   ├── B2
│   └── C1
└── 02-COCA
    ├── 01k
    ├── 02k
    ├── 03k
    ├── ...
    └── 20k
```

- `01-CEFR` contains meanings graded A1–C1, including core meanings outside the 20k frequency range. Placement follows each meaning's level, so different meanings of one word can appear at different levels.
- `02-COCA` contains the remaining included meanings in twenty 1k frequency bands. Start with `01k` and work toward `20k`.
- Study the parent deck for both sections, or select a level or frequency band to focus your reviews.

Each card teaches one meaning. A word with several meanings therefore has several cards; suspend individual meanings you already know or do not need.

## Card features

![Card fronts, backs, and translations in light and dark themes, including hidden translations and optional example TTS](https://pub-90b0b2afa26447b8b824c3d05d8e274f.r2.dev/uPic/20261020eNTkHo.png)

*Some previews have translations and TTS enabled; both are off by default.*

- Front: the headword and one randomly selected example from the card.
- Back: one English definition, up to three examples, and available grammar, usage, and collocation labels.
- Pronunciation: British and American IPA and audio. Blue speaker buttons indicate British audio; rose buttons indicate American audio. Included recordings work offline.
- Translations: enable Simplified Chinese, Japanese, or both. Tap a translation bar to reveal or hide it, or use the translation icon / `L` to toggle all translations. `[AI]` marks AI-generated translations.
- Example TTS: optional online speech for examples without recordings, identified by an `AI` badge on the speaker button.
- Quick lookup: click the Oxford logo to look up the word online.
- Appearance: responsive light and dark layouts, with bundled English, IPA, Chinese, and Japanese fonts.

## Download and import

Choose one file from [GitHub Releases](https://github.com/5mdld/anki-english-oald-decks/releases):

| File | Approximate size | Audio |
| --- | --- | --- |
| `eggrolls-oald-20k.apkg` | ~1 GB | Word audio and included example recordings |
| `eggrolls-oald-20k-no-example-audio.apkg` | ~300 MB | Word audio; optional online TTS for examples |

Sizes may vary by release.

Both versions contain the same cards, examples, translations, and subdecks. They share the same note identities; when switching versions, allow Anki to update existing notes.

1. Install [Anki](https://apps.ankiweb.net/), then open File → Import and select the `.apkg` file.
2. Enable Import any deck presets if offered, to use the included review settings.
3. Select `eggrolls-OALD-20k` or one of its subdecks and start reviewing.
4. To study on another device, sync your collection and media after importing or changing the settings below.

## User settings

On desktop Anki, open Browse → select a card from this deck → Cards… → Back Template. Find `USER SETTINGS` near the beginning of the `<script>` section, edit the desired `true` / `false` values, then save and close.

These switches apply to all cards using the `eggrolls-OALD` note type.

| Setting | Default | Behavior |
| --- | --- | --- |
| `showBrE` | `true` | `true`: show British IPA and audio controls. `false`: hide both. |
| `showAmE` | `true` | `true`: show American IPA and audio controls. `false`: hide both. |
| `enableExampleTTS` | `false` | `true`: add online TTS buttons to examples without recordings. `false`: use included recordings only. |
| `forceHeadwordAutoplay` | `true` | `true`: play the first available enabled word recording on the back, British first. `false`: disable the template's autoplay. |
| `showChinese` | `false` | `true`: enable Chinese definition and example translations. `false`: hide them. |
| `showJapanese` | `false` | `true`: enable Japanese definition and example translations. `false`: hide them. |
| `showTranslationsInitially` | `false` | `true`: show enabled translations immediately. `false`: hide them until you tap a bar, click the translation icon, or press `L`. |

Enable at least one language to display translation bars and the translation icon. For both languages, set both language switches to `true`. TTS requires an internet connection and follows the enabled accent settings.

### Review and audio options

Open the gear icon beside the deck → Options to adjust daily limits and study order.

**Keep Don't play audio automatically enabled** under Deck Options → Audio when using the template's word autoplay, to avoid duplicate or additional playback. For manual playback only, also set `forceHeadwordAutoplay: false`.

The root deck and its subdecks share the same preset. After importing an update that replaces the card templates, check your user settings again.
