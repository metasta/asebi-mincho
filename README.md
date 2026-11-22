# 馬酔木明朝 2 / Asebi Mincho 2

馬酔木（あせび）明朝 2は、日本語の漢字を旧字形で表示する明朝体です。漢字は一点明朝正字を基準とし、かな・約物・欧文の主な素材は錦明朝です。

[配布先の GitHub Releases](https://github.com/metasta/asebi-mincho/releases)

![馬酔木明朝 2の書体見本。横組みは雨の後の窓、縦組みは古本から落ちる花。文脈による字形の例は雄辯・辨別・花瓣。](asebi-specimen.png)

## 収録範囲

漢字11,810字を収録します。対象はJIS X 0213の第1〜第4水準、Unicodeの互換漢字2ブロック、青空文庫でUnicode符号位置が明記された外字です。複数の範囲に属する字は1字分です。配布ZIPの `収録漢字.txt` で確認できます。「𛀀」（ア行）と「𛀁」（ヤ行）も収録します。

## 利用方法

配布ZIPを展開し、`AsebiMincho2-Light.otf` をインストールします。Wordなどのアプリでは「馬酔木明朝 2」または「Asebi Mincho 2」を選びます。ウェイトはLightです。旧版の馬酔木明朝と併用できます。

### 文脈による同形異字の区別

「辯」「辨」「瓣」は、今の表記では同じ「弁」と書く別の漢字です。文脈による字形選択に対応する組版環境では、「雄弁」「弁別」「花弁」を、それぞれ「雄辯」「辨別」「花瓣」の字形で表示します。コピーや検索は、入力した文字コードに基づきます。「弁」の直後に異体字セレクタ U+E0100 を入力すると、「弁」の字形を指定できます。

### 旧版からの字形の変更

旧版の「校」「文」では、右下へ伸びる画の起筆に小さな跳ねがありました。新版では字形基準に従って、この跳ねを省きました。 [一点明朝正字の字形選定基準](https://github.com/epistularum/kanji-restoration#正字-criteria)・[旧版のサイト](https://metasta.github.io/asebi/)

### 縦組みでの三点リーダ

Mac版Wordなどでは、横組み用の字形が回転し、縦組みの三点リーダ `…`（U+2026）が行の中央より左に寄る場合があります。中央に配置するには、縦組み用の互換文字 `︙`（U+FE19）を入力します。2字続ける場合は `︙︙` と入力します。 [Unicodeの縦組み三点リーダの説明](https://www.unicode.org/versions/Unicode17.0.0/core-spec/chapter-6/)

## 使用許諾と素材

馬酔木明朝 2は、IPAフォントライセンスv1.0に従って配布します。配布ZIPには、フォントの著作権表示、素材の詳細、再加工用のOpenTypeテーブル（TTX）、原版へ戻す手順が含まれます。 [ライセンス原文](IPA_Font_License_Agreement_v1.0.txt)

漢字の基準と輪郭は一点明朝正字 v1.1、かな・約物・欧文の主な素材は錦明朝 1.111です。一部に三番明朝 1.001とIPAmj明朝 006.01も採用しました。派生版に関する質問は、このリポジトリのIssuesで受け付けます。 [一点明朝正字](https://github.com/epistularum/kanji-restoration/releases/tag/v1.1)・[錦明朝](https://www.akenotsuki.com/eyeben/fonts/nishiki.html)・[三番明朝](https://www.akenotsuki.com/eyeben/fonts/sammin.html)・[IPAmj明朝](https://moji.or.jp/mojikiban/font/)
