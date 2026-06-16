# IPA Phonemic Typewriter

A single-page British English IPA keyboard for building phonemic transcriptions. Click keys to insert symbols into a text area, then copy the result anywhere.

## Features

- **44 phonemes** covering all British English sounds — short vowels, long vowels, diphthongs, plosives, fricatives, affricates, nasals, and approximants
- **Color-coded keys** by phoneme category with a legend
- **Hover tooltips** with the phoneme name and example words (toggleable)
- **Cursor-aware insertion** — clicking a key inserts at the current caret position, respecting selections
- **Unicode-safe delete** — handles multi-codepoint IPA characters correctly
- **Copy to clipboard** with visual confirmation
- Keyword labels use **J.C. Wells' lexical sets** (e.g. FLEECE, KIT, TRAP)
- Fully responsive down to narrow mobile screens
- No build step, no dependencies — a single `index.html` file

## Usage

Open `index.html` in any modern browser. No server required.

- Click phoneme keys to insert symbols at the cursor
- Type directly in the output box if needed
- Use **Delete** to remove the character before the cursor (Unicode-safe)
- Use **Space** to insert a word boundary
- Use **Clear** to reset the output
- Use **Copy** to copy the transcription to the clipboard
- Toggle **Tips** to show or hide hover tooltips

## Phoneme Coverage

| Category | Symbols |
|---|---|
| Short vowels | ɪ e æ ʌ ɒ ʊ ə |
| Long vowels | iː uː ɜː ɔː ɑː |
| Diphthongs | ɪə eɪ ʊə ɔɪ əʊ eə aɪ aʊ |
| Plosives | p b t d k g |
| Fricatives | f v θ ð s z ʃ ʒ h |
| Affricates | ʧ ʤ |
| Nasals | m n ŋ |
| Approximants | l r w j |
| Stress markers | ˈ ˌ |

## Credits

- Phoneme keywords from [J.C. Wells' lexical sets](https://en.wikipedia.org/wiki/Lexical_sets)
- Symbols are standard Unicode — paste into Word, Google Docs, or any Unicode-aware app
- Font rendering via [Noto Sans](https://fonts.google.com/noto/specimen/Noto+Sans)
