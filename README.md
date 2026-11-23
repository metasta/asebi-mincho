# 馬酔木明朝 / Asebi Mincho

[English](README.en.md)

馬酔木（あせび）明朝は、一点明朝正字の基準に沿った字形で日本語を組むための明朝体です。

[フォントをダウンロード](https://github.com/metasta/asebi-mincho/releases)

## 利用方法

配布ZIPを展開し、`AsebiMincho2-Light.otf` をインストールします。アプリのフォントメニューで「馬酔木明朝 2」または「Asebi Mincho 2」を選びます。旧版と併用するため、メニュー上の登録名には「2」が付きます。ウェイトはLightです。

### Webブラウザ

ChromeやFirefoxでは、インストールしたフォントを既定フォントに指定できます。この設定は、ブラウザの既定フォントに任せた箇所に適用されます。サイトが独自にフォントを指定した箇所は、そのフォントで表示される場合があります。 [Chromeの設定](https://support.google.com/chrome/answer/96810?hl=ja)・[Firefoxの設定](https://support.mozilla.org/ja/kb/change-fonts-and-colors-websites-use)

macOS版Safariの設定には、既定フォントを選ぶ項目がありません。「詳細」からユーザースタイルシート（CSS）を指定できます。Safariのプライバシー保護機能により、ページから利用者が追加したフォントの参照が制限される場合もあります。 [Safariの詳細設定](https://support.apple.com/en-ie/guide/safari/ibrw1075/mac)・[WebKitのプライバシー保護](https://webkit.org/tracking-prevention/)

## 旧版からの変更点

### 字形の基準

旧版は『角川 新字源』を基準とした旧字明朝です。新版は、字源や日本語での用法を考慮する一点明朝正字の基準を採用した正字明朝です。「校」「文」では、右下へ伸びる画の始めにあった小さな跳ねを省きました。 [旧版の解説](https://metasta.github.io/asebi/)・[一点明朝正字の字形選定基準](https://github.com/epistularum/kanji-restoration#正字-criteria)

バージョン2.000は、JIS X 0213の第1〜第4水準、Unicodeの互換漢字、青空文庫の外字注記に由来する漢字を計11,810字収録します。

### 複数の正字を持つ漢字への対応

「辯」「辨」「瓣」は、今の表記では同じ「弁」と書く別の漢字です。OpenTypeの `calt` が有効な組版環境では、「雄弁・弁別・花弁」を「雄辯・辨別・花瓣」の字形で表示します。

文脈に必要な文字が別々の行に分かれると、アプリによっては規則が適用されません。画面幅や文字サイズによる自動改行でも、同じ入力で字形が異なる場合があります。

一人称の「余」や「予」をそのままの字形で表示するには、異体字シーケンス（IVS）に対応する環境で `余󠄀` または `予󠄀` を入力します。それぞれ漢字の直後に異体字セレクタ U+E0100 を置きます。馬酔木明朝では、この方法で対応表の17組を指定できます。 [文脈規則とIVSの対応表](docs/contextual-forms.md)

## 技術資料

- [漢字の収録範囲と青空文庫の外字](docs/coverage.md)
- [漢字の選定基準と一点明朝正字との字形差](docs/glyph-differences.md)
- [文脈による字形選択と異体字シーケンス](docs/contextual-forms.md)
- [既知の不具合と対処法](docs/known-issues.md)

## 使用許諾と素材

馬酔木明朝はIPAフォントライセンスv1.0で配布します。配布ZIPには、各素材の著作権表示、原版へ戻す手順、再加工用のOpenTypeテーブル（TTX）が含まれます。 [ライセンス原文](IPA_Font_License_Agreement_v1.0.txt)

漢字の主な素材は一点明朝正字 v1.1、かな・約物・欧文の主な素材は錦明朝 1.111です。一部に三番明朝 1.001とIPAmj明朝 006.01も採用しました。 [一点明朝正字](https://github.com/epistularum/kanji-restoration/releases/tag/v1.1)・[三番明朝](https://www.akenotsuki.com/eyeben/fonts/sammin.html)・[IPAmj明朝](https://moji.or.jp/mojikiban/font/)

錦明朝 1.111には独自のライセンスが適用されます。最終版の錦明朝 3.000はSIL Open Font License 1.1で配布されました。 [錦明朝 3.000の配布条件](https://www.akenotsuki.com/eyeben/fonts/nishiki.html)

馬酔木明朝に関する質問や不具合の報告は、GitHub Issuesで受け付けます。 [Issues](https://github.com/metasta/asebi-mincho/issues)
