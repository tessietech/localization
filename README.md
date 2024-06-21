# What's this?

Localization data used across the Tessie platform.

Filenames follow the two-letter language code ISO standard. See https://en.wikipedia.org/wiki/List_of_ISO_639_language_codes for a complete list.

# Requesting a new language

Create an issue with your requested language so that others can vote on it.

# Submitting corrections and improvements

Language is originally defined in [en.json](https://github.com/tessietech/localization/blob/main/en.json), so please use it as your source reference.

Edit your language file in any text editor, changing the strings on the right side:

```
"youShouldIgnoreThis": "You should fix this part to be correct. {youCanMoveThisVariableButNotRenameIt}"
```

Submit a pull request and your edits will be promptly reviewed.

**Do not modify:**

* Punctuation - for example, adding or removing periods
* Units of measurement - for example, converting between imperial and metric
* Variable names - for example, changing {value} to {newValue}
