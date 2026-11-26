# 漢字の収録範囲

馬酔木明朝で表示したい漢字は、配布ZIPの `収録漢字.txt` で収録の有無を確認できます。2.001の収録漢字は12,101字です。表では、複数の範囲に共通するUnicodeの文字番号（符号位置）を1字とします。 [配布ZIPの入手先](https://github.com/metasta/asebi-mincho/releases)

| 収録の根拠 | 範囲内の字数 | 上の行と重複しない字数 |
| --- | ---: | ---: |
| JIS X 0213:2004の第1〜第4水準 | 10,050 | 10,050 |
| UnicodeのCJK互換漢字・CJK互換漢字補助の2ブロック | 1,014 | 932 |
| 青空文庫の外字注記からUnicode符号位置を特定した漢字 | 840 | 828 |
| 互換漢字の正準対応先 | 902 | 291 |
| 合計 | | 12,101 |

## JIS X 0213:2004

第1水準から第4水準までの漢字を収録します。内訳は、第1水準2,965字、第2水準3,390字、第3水準1,259字、第4水準2,436字です。集計では、規格に記載の文字番号（面区点番号）をCPythonの `euc_jis_2004` でUnicodeに変換し、漢字1字に対応するものを採録しました。 [Python標準ライブラリの文字コード表](https://docs.python.org/ja/3/library/codecs.html#standard-encodings)

## Unicodeの互換漢字と正規化

Unicodeの「CJK互換漢字」（U+F900–U+FAFF）と「CJK互換漢字補助」（U+2F800–U+2FA1F）に割り当てのある1,014字を、各符号位置で収録します。このうち1,002字には、Unicodeが同じ文字とみなす別の符号位置（正準対応先）があります。残る12字はCJK互換漢字ブロック内の統合漢字です。集計ではUnihan 18.0.0の `kCompatibilityVariant` を参照しました。 [Unicode規格の漢字の章](https://www.unicode.org/versions/Unicode18.0.0/core-spec/chapter-18/)・[Unihanのプロパティ定義](https://www.unicode.org/reports/tr38/tr38-41.html#kCompatibilityVariant)

正準対応先がある互換漢字は、Unicode正規化（NFCなど）を経ると、その対応先の符号位置に変換されます。「徚」（U+2F89C）が「徚」（U+5F9A）になるのが一例です。2.001では正準対応先902字をすべて収録し、各組で同じ既定の字形を表示します。 [Unicode正規化仕様](https://www.unicode.org/reports/tr15/#Respecting_Canonical_Equivalence)・[互換漢字補助の符号表](https://www.unicode.org/Public/18.0.0/charts/nameslist/2f800/)

## 青空文庫の外字

青空文庫の作品テキストでは、JIS X 0208の第1・第2水準にない漢字を `※［＃…］` の形式で注記します。「外字注記」と呼ぶこの記載には、字の構成や底本の頁・行のほか、JIS X 0213やUnicodeの文字番号が入る場合があります。青空文庫の『外字注記辞書』は作品入力時の資料で、注記の書式や、JISの規則で代用できる字を掲載します。 [青空文庫の外字注記の規定](https://www.aozora.gr.jp/annotation/external_character.html)・[青空文庫・外字注記辞書](https://www.aozora.gr.jp/gaiji_chuki/)

馬酔木明朝では、実際に作品に出現する外字を集めるため、青空文庫の作品テキストから直接集計しました。参照したのは `aozorahack/aozorabunko_text` の2023年3月22日版で、`cards/` 以下の17,436ファイルが対象です。外字注記を抜き出し、`U+…` の形式で漢字1字を特定できる場合に、その字を採録しました。字の構成だけを記した注記や、この版より後の作品は集計の対象外です。JIS X 0213の番号が記された漢字は、表のJISの範囲に含まれます。 [参照したテキストの版](https://github.com/aozorahack/aozorabunko_text/commit/0984f7dc18a2270bdfd2ff99bf14fd1b3ebb4f65)

木暮理太郎「二、三の山名について」の外字注記には、`U+28506` とあります。馬酔木明朝では、この符号位置の「𨔆」を収録します。本文の一字として表示するには、注記に対応するUnicode文字「𨔆」を入力します。 [青空文庫「二、三の山名について」](https://www.aozora.gr.jp/cards/001373/files/56553_54437.html)
