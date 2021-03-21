## Localization help - Hitori

You can help us localize Hitori. Follow these instructions:
1. Download [sample localization files](https://github.com/DaintyGames/DaintyGames.github.io/raw/master/localization-help/hitori.zip).
1. Translate from any language among the examples of localization files to yours into a file named ```locale_new.json```
1. Send the localized file to [games.dainty@gmail.com](mailto:games.dainty@gmail.com). You need to specify the language in the message or rename your file to ```locale_<code>.json```, where ```<code>``` is the two-letter country code and (optionally) the two-letter region code. You can find your code [here](https://github.com/L-P/native-language-list/blob/master/data/langs.csv).
1. Also indicate if you want to update the localization when we add new texts.

Translation requirements
-------------------
1. Please do not use Google Translate or use it as little as possible and check the results for human readability.
1. Key-value pairs that are grouped must be in the same context
1. Constructions like ```{0}``` are not localized, they are labels that will be replaced with some value during the game.
1. You can omit line breaks ```\n```

File structure
--------------
The localization file consists of key-value pairs. Example:
```json
{
  "data": {
    "group_1.key_1": "string",
    "group_1.key_2": "string",

    "group_2.key_1": "string",
    "group_2.key_2": "string"
  }
}
```
The key describes what the string refers to. Keys are grouped according to common characteristics, for example, to a certain screen.

If you help us
---------------
We will leave your name or mail on the thanks page on the settings screen! :^)
