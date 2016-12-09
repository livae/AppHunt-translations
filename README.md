# AppHunt-translations

## For non-developers

1. Download the [English file](https://raw.githubusercontent.com/livae/AppHunt-translations/master/values/strings.xml) or the language specific file. The translations are under the directories values-XX where XX is the language code.
2. Read first: [How resources files works in android](https://developer.android.com/guide/topics/resources/string-resource.html)
3. More considerations when translating: 
    - `<string name="xxxx">TRANSLATE_THIS_PART</string>`
    - Remove lines with this comment: `translatable="false"`
    - `%1$s` and everything that starts with `%` are variables, keep them in the same position as they are.
    - `\n` and `\t` are break lines and spaces, keep them in the same position.
    - `<em>`, `<b>`, `<i>`, etc. Are html tags, keep them too.
    - `@string/xxxx` are references of other translations, remove those lines.
    - `...` is one character and not 3 dots, copy paste it from other places.
    - Do not add extra spaces at the end of the beginning of the translation.
4. (Optional) You can translate the PlayStore description, these are the files named shortdescription_80chars (maximum 80 characters) and fulldescription
5. Send me the file by email: apphunt@livae.com

## For developers

1. Read first: [How resources files works in android](https://developer.android.com/guide/topics/resources/string-resource.html)
2. Edit the xml files to add the missing resources (use Android studio to simplify it, otherwise they are listed at the end of the file)
3. (Optional step) Sort the xml file, you can use the xslt template `sort.xls`. In linux you can use `xsltproc`.
4. (Optional) You can translate the PlayStore description, these are the files named shortdescription_80chars (maximum 80 characters) and fulldescription
5. Edit this file to add your name in the collaborators if you want to appear in the PlayStore description.
6. Make a pull requests with the changes

# Collaborators

- English: AppHunt team
- Spanish (ES): AppHunt team
- Turkish (TR):  [Kutsan Kaplan](https://github.com/Kutsan)
- German (DE): Philipp Dormann
- Hindi (HI): Pratyush Jar
- Dutch (NL): Ben Hendrickx
