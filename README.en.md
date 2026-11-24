# Asebi Mincho / 馬酔木明朝

[日本語](README.md)

Asebi Mincho is a Japanese serif typeface for setting text in traditional kanji forms.

[Download the font](https://github.com/metasta/asebi-mincho/releases)

![Horizontal text from Ten Nights of Dreams and vertical text from Tangled Hair, both with ruby readings](asebi-specimen.png)

[Natsume Sōseki, Ten Nights of Dreams, First Night](https://www.aozora.gr.jp/cards/000148/files/799_14972.html) · [Yosano Akiko, Tangled Hair](https://www.aozora.gr.jp/cards/000885/files/51307_47033.html)

## Installation

Extract the release ZIP and install `AsebiMincho2-Light.otf`. The family name is **Asebi Mincho 2** in English and **馬酔木明朝 2** in Japanese. The PostScript name is `AsebiMincho2-Light`, and the weight is Light. You can install this edition alongside the previous one.

Set Asebi Mincho as your browser’s default font to use it wherever a site relies on that default. In browsers without a default font picker, such as Safari on macOS, a user style sheet may let you apply the font.

[Chrome settings](https://support.google.com/chrome/answer/96810?hl=en) · [Firefox settings](https://support.mozilla.org/en-US/kb/change-fonts-and-colors-websites-use) · [Safari settings](https://support.apple.com/en-ie/guide/safari/ibrw1075/mac) · [WebKit’s tracking prevention](https://webkit.org/tracking-prevention/)

## Changes from the previous edition

### Kanji coverage and glyph selection

Version 2.000 covers 11,810 kanji in total, drawn from levels 1–4 of JIS X 0213, the two Unicode CJK Compatibility Ideographs blocks, and Aozora Bunko’s annotations for kanji outside JIS X 0208.

Most kanji in this edition use glyphs from I.Ming Seiji v1.1. This edition applies the same selection criteria to kanji absent from that font and to kanji whose original checks against sources could not be confirmed. [I.Ming Seiji v1.1](https://github.com/epistularum/kanji-restoration/releases/tag/v1.1) · [Selection criteria](https://github.com/epistularum/kanji-restoration#正字-criteria)

The previous edition selected traditional forms using Kadokawa’s *Shinjigen* dictionary. The new criteria base glyph selection on character origins. One visible change is the removal of some decorative details from traditional Mincho printing type, including the small hook at the start of the right-falling stroke in 文 and 校. [Previous edition](https://metasta.github.io/asebi/)

### Distinguishing kanji that share a modern form

#### Selecting forms with ideographic variation sequences

餘 (“remainder”) and 余 (a first-person pronoun) are distinct kanji that share the form 余 in modern Japanese. Asebi Mincho displays 余 as 餘 by default. To display the form 余 in an app that supports ideographic variation sequences (IVS), enter `余󠄀` (余, U+4F59, followed by variation selector U+E0100). This option covers 17 kanji, including 余, 予, 灯, and 芸.

#### Selecting forms automatically from context

辯, 辨, and 瓣 are distinct kanji that share the form 弁 in modern Japanese. 雄弁 appears as 雄辯 by default. With the OpenType `calt` feature enabled, 弁別 and 花弁 appear as 辨別 and 花瓣, respectively. The contextual rules cover 10 kanji, including 弁, 芸, 台, and 欠.

These rules apply to the character sequences registered in the font. A line break within a sequence can prevent a rule from applying, even when the app inserts the break automatically. To get the intended forms regardless of line breaks, enter 雄辯, 辨別, or 花瓣 directly.

[Contextual rules and IVS reference (Japanese)](docs/contextual-forms.md)

## Technical documentation

The following documents are in Japanese.

- [Kanji coverage and Aozora Bunko character notes](docs/coverage.md)
- [Kanji selection and glyph differences from I.Ming Seiji](docs/glyph-differences.md)
- [Contextual forms and ideographic variation sequences](docs/contextual-forms.md)
- [Known issues and workarounds](docs/known-issues.md)

## License and sources

Asebi Mincho is distributed under the IPA Font License Agreement v1.0. The release ZIP includes copyright notices for the source fonts, instructions for reverting to the original typefaces, and editable OpenType table data in TTX format. [License text](IPA_Font_License_Agreement_v1.0.txt)

Nishiki Mincho 1.111 is the main source for kana, punctuation, and Latin characters, with additional material from Sanban Mincho 1.001 and IPAmj Mincho 006.01. [Sanban Mincho](https://www.akenotsuki.com/eyeben/fonts/sammin.html) · [IPAmj Mincho](https://moji.or.jp/mojikiban/font/)

Nishiki Mincho 1.111 was distributed under its own license. The final release, Nishiki Mincho 3.000, was distributed under the SIL Open Font License 1.1. [Nishiki Mincho 3.000 license information](https://www.akenotsuki.com/eyeben/fonts/nishiki.html)

Questions and bug reports are welcome on GitHub. [Issues](https://github.com/metasta/asebi-mincho/issues)
