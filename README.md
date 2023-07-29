# Anki-Mining-Template
I wanted clickable images and separated definitions like the [jp-mining-note](https://github.com/Aquafina-water-bottle/jp-mining-note), but simple code and design like [Anime Cards](https://github.com/friedrich-de/Basic-Mining-Deck), so I made this. 

## The note
<img src="https://github.com/Maltesaa/Anki-Mining-Template/assets/66385422/82055a30-580f-45b2-b62b-282f509d5591" width="1080"/>

## Features
- Easy customization
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
|SentenceCard||
|TargetedSentenceCard||

### Without using the jp-mining-note Yomichan template
Same as jp-mining-note except for these fields:

|Fields  |Value   |
|--------|--------|
|PrimaryDefinition|{selection-text}|
|SecondaryDefinition||
|ExtraDefinitions|{glossary}|

## Transfering from Anime Cards
Pair the glossary field to PrimaryDefinitions. This will show the first definition in the list as the primary definition and the rest will be shown under extra definitions.

## Todo
- [ ] Make secondary definitions work without a custom handlebar
