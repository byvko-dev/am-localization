### Feel free to open PRs for missing translations and improvements.
#

The main branch of this repo is used as the definitive localization config for all supported Aftermath services. Currently, all translations live in the same file, though this is something I can change once the file size gets too large.

To create a translation for this language, just commit a file names `{code}.yml` where `code` is the language code.

Here is a list of all languages that are officially supported by Wargaming:  
```
"en"    // English
"ru"    // Russian
"pl"    // Polish
"de"    // German
"fr"    // French
"es"    // Spanish
"tr"    // Turkish
"cs"    // Czech
"th"    // Thai
"ko"    // Korean
"vi"    // Vietnamese
"zh-cn" // Simplified Chinese
"zh-tw" // Traditional Chinese
```
*Those languages will have translations for tank names and achievements, any languages not on this list will use English tank and achievement names.*

#

### How to upload translation to Translized:
*You will probably never need to use this*
- Install [TaskFile](https://taskfile.dev/)
- Get your project ID and access token from https://app.translized.com and place them into `.env`
- Run `task upload` for English and `task upload -- {code}` for any other language.