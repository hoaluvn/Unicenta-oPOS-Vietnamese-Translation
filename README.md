OpenBravo POS Vietnamese Translation
====================================
- Target version: 2.80
- Final target: Unicenta oPOS

Tool
====================================
- Translate Toolkit & Pootle
  + Convert *.properties files <-> *.po files
  + URL: http://translate.sourceforge.net/wiki/toolkit/index

- Poedit
  + Translation tool
  + URL: www.poedit.net

How to translate
====================================
- For the first time, I had to convert *.properties -> *.po
  $ prop2po locales po/locales
- Use Poediter to translate po/locales/*.po to Vietnamese

- Convert *.po -> *.properties
  $ po2prop po/locales vi_VN/locales -t locales

Install
====================================
- cp vi_VN/locales/*.properties $TARGET/locales/*_vi_VN.properties
