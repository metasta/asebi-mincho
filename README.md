# 馬酔木明朝 2 / Asebi Mincho 2

馬酔木（あせび）明朝 2は、日本語の漢字を旧字形で表示する明朝体です。「学校の図書館」と入力すると、「學校の圖書館」の字形で表示します。漢字は一点明朝正字を基準とし、かな・約物・欧文は錦明朝を主体としています。

[配布先の GitHub Releases](https://github.com/metasta/asebi-mincho/releases)

![馬酔木明朝 2で、横組みの「庭の木々に、静かな春が来る。」と縦組みの短文を表示した書体見本](asebi-specimen.png)

## 収録範囲

漢字11,810字を収録します。対象はJIS X 0213の第1〜第4水準、Unicodeの互換漢字2ブロック、青空文庫でUnicode符号位置が明記された外字です。重複は1字として数えています。配布ZIPの `収録漢字.txt` で確認できます。ア行エ「𛀀」とや行え「𛀁」も収録します。

## 使い方

配布ZIPを展開し、`AsebiMincho2-Light.otf` をインストールします。Wordなどのアプリでは「馬酔木明朝 2」または「Asebi Mincho 2」を選びます。ウェイトはLightです。旧版の馬酔木明朝と併用できます。

文脈による字形の切り替えに対応する組版環境では、「台」は単独で「臺」、天台では「台」、台頭では「擡」、台風では「颱」の字形で表示されます。「台」の直後に異体字セレクタ U+E0100 を入力すると、「台」の字形を指定できます。文脈による切り替えは17字・137規則に対応します。コピーや検索には入力した文字コードが使われます。

新版は、旧版の「校」「文」にあった右払いの筆押さえを、字形基準に合わせて省きました。[一点明朝正字の字形選定基準](https://github.com/epistularum/kanji-restoration#正字-criteria)・[旧版のサイト](https://metasta.github.io/asebi/)

### 縦組みでの三点リーダ

Mac版Wordなどでは、横組み用の字形を回転して使うため、縦組みの三点リーダ `…`（U+2026）が行の中央より左に見えることがあります。中央に揃えるには、縦組み用の互換文字 `︙`（U+FE19）を使います。2字続ける場合は `︙︙` と入力します。 [Unicodeの縦組み三点リーダの説明](https://www.unicode.org/versions/Unicode17.0.0/core-spec/chapter-6/)

## 使用許諾と素材

馬酔木明朝 2は、IPAフォントライセンスv1.0に従って配布します。フォントの著作権表示、素材の詳細、再加工用のOpenTypeテーブル（TTX）と原版へ戻す手順は、配布ZIPに収めています。[ライセンス原文](IPA_Font_License_Agreement_v1.0.txt)

漢字の基準と輪郭は一点明朝正字 v1.1、かな・約物・欧文の主な素材は錦明朝 1.111です。一部に三番明朝 1.001とIPAmj明朝 006.01を使用しています。派生版へのお問い合わせは、このリポジトリのIssuesへお願いします。[一点明朝正字](https://github.com/epistularum/kanji-restoration/releases/tag/v1.1)・[錦明朝](https://www.akenotsuki.com/eyeben/fonts/nishiki.html)・[三番明朝](https://www.akenotsuki.com/eyeben/fonts/sammin.html)・[IPAmj明朝](https://moji.or.jp/mojikiban/font/)
