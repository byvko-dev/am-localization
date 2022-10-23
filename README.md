### Feel free to open PRs for missing translations and improvements.
#

The main branch of this repo is used as the definitive localization config for all supported Aftermath services. Currently, all translations live in the same file, though this is something I can change once the file size gets too large.

Here is a list of all languages that can be supported:
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

To create a translation for this language, just commit a file names `{code}.yml` where `code` is the language code.

#

### How to upload translation to Translized:
- Install [TaskFile](https://taskfile.dev/)
- Get your project ID and access token from https://app.translized.com and place them into `.env`
- Run `task upload` for English and `task upload -- {code}` for any other language.