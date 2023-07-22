# Anki-Mining-Template
I wanted clickable images and separated definitions like the [jp-mining-note](https://github.com/Aquafina-water-bottle/jp-mining-note), but the simplicity and look of the [Anime Card](https://github.com/friedrich-de/Basic-Mining-Deck) note, so I made this.

## The note
<img src="https://user-images.githubusercontent.com/66385422/255272167-3ff7ca00-ab41-4cdd-ba2b-e424f9b49a49.gif" width="810"/>


## Features
- Can be easily customized in the styling section
- Works for both dark and light mode
- Support for Vocab Cards, Sentence Cards and Targeted Sentence Cards
- Clickable Images
- Primary, Secondary and Extra definitions like on [jp-mining-note](https://github.com/Aquafina-water-bottle/jp-mining-note)

## Yomichan Fields
### Using the jp-mining-note's Yomichan template
Put anything (ex. "x") in the SentenceCard or the TargetedSentenceCard fields depending on what you want.

|Fields  |Value   |
|--------|--------|
|Word|{expression}|
|Reading|{furigana}|
|Sentence|{sentence}|
|SentenceBold|{cloze-prefix}\<b>{cloze-body}\</b>{cloze-suffix}|
|Image||
|PitchGraph|{pitch-accent-graphs}|
|WordAudio|{audio}|
|SentenceAudio||
|PrimaryDefinition|{jpmn-primary-definition}|
|SecondaryDefinition|{jpmn-secondary-definition}|
|ExtraDefinitions|{jpmn-extra-definitions}|
|ExtraInfo||
|Frequency|{jpmn-frequency-sort}|
|Blur||
|SentenceCard||
|TargetedSentenceCard||

### Without using the jp-mining-note Yomichan template
Same as the jp-mining-note one but change these fields.

|Fields  |Value   |
|--------|--------|
|PrimaryDefinition|{glossary}|
|SecondaryDefinition||
|ExtraDefinitions||

## Todo
- [ ] Implement frequency display
- [ ] Fine tune styling and clean up code
- [x] Add support for transfering from Anime Cards
