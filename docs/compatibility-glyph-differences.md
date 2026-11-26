# 互換漢字の採用字形と根拠

馬酔木明朝2.000に収録した互換漢字のうち、一点明朝正字 v1.1 に同じ符号位置がないものを、同フォントで正準対応先に割り当てられた字形と比較しました。ここでは差がある61件を示します。同じ符号位置の字形を比較した結果と次版の変更は、[漢字の選定基準と字形差](glyph-differences.md)を参照してください。 [Unicode正規化仕様](https://www.unicode.org/reports/tr15/#Respecting_Canonical_Equivalence)

## 字書の照合で選定した58件

一点明朝正字の基準に沿って、字書に記された異体関係や字の成り立ちを確認し、本文用の字形を選定しました。「字形の参照先」の字は、一点明朝正字から輪郭を取得する際の指定を示します。 [一点明朝正字 v1.1 の選定基準とフロー](https://github.com/epistularum/kanji-restoration/blob/v1.1/README.md#正字-criteria)

| 入力字 | 正準対応先 | 字形の参照先 | 根拠 |
| --- | --- | --- | --- |
| 𢡊（`U+FACF`） | 𢡊（`U+2284A`） | 愆 | 『漢語大字典』は𢡊を愆と同字とします。 [漢語大字典2518頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=2518) |
| 𢡄（`U+FAD0`） | 𢡄（`U+22844`） | 憯 | 『漢語大字典』は𢡄を憯と同字とします。 [漢語大字典2518頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=2518) |
| 𥉉（`U+FAD5`） | 𥉉（`U+25249`） | 𥉈 | 『康熙字典』所引の『正字通』は、條を含む𥉉を𥉈の訛字とします。 [字書の該当項](https://ctext.org/dictionary.pl?char=%F0%A5%89%89&if=en) |
| 龎（`U+FAD9`） | 龎（`U+9F8E`） | 龐 | 『異體字字典』所引の『說文解字』によると、高い建物を表す龐は广を含み、龍が声符です。 [異體字字典](https://dict.variants.moe.edu.tw/dictView.jsp?ID=13537) |
| 丽（`U+2F800`） | 丽（`U+4E3D`） | 麗 | 『異體字字典』は丽を麗の異体とし、麗の古文に由来する形とします。 [異體字字典](https://dict.variants.moe.edu.tw/dictView.jsp?educode=A04756-002) |
| 𠔜（`U+2F812`） | 𠔜（`U+2051C`） | 坤 | 『漢語大字典』『異體字字典』は𠔜を坤と同字とします。『說文解字』の坤は土と申を含みます。 [漢語大字典127頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=127)・[異體字字典](https://dict.variants.moe.edu.tw/dictView.jsp?ID=7770) |
| 㒹（`U+2F813`） | 㒹（`U+34B9`） | 顛 | 『漢語大字典』は眞を二つ並べる㒹を顛の異体とします。頁を含む字形は一点明朝正字の顛の選定形です。 [漢語大字典132頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=132) |
| 仌（`U+2F819`） | 仌（`U+4ECC`） | 冰 | 『漢語大字典』『康熙字典』は仌を冰と同字とします。 [漢語大字典136頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=136) |
| 𩇟（`U+2F81C`） | 𩇟（`U+291DF`） | 儬 | 『異體字字典』は冷寒を表す㵾の異体に𩇟を挙げます。一点明朝正字で儬に割り当てる㵾の字形は、水偏と声符の靚から成ります。 [異體字字典](https://dict.variants.moe.edu.tw/dictView.jsp?ID=90678&la=0) |
| 𠭣（`U+2F838`） | 𠭣（`U+20B63`） | 豚 | 『異體字字典』は𠭣を豚の異体とします。『說文解字』に併載の肉と豕の構成を採用しました。 [異體字字典](https://dict.variants.moe.edu.tw/dictView.jsp?ID=42614) |
| 𡧈（`U+2F86C`） | 𡧈（`U+219C8`） | 宇 | 『漢語大字典』は宀＋亐の𡧈を宇と同字とします。宇には声符の于があります。 [漢語大字典978頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=978) |
| 𡷤（`U+2F87B`） | 𡷤（`U+21DE4`） | 峿 | 『漢語大字典』は山を形容する峿と𡷤を同字とし、『異體字字典』も異体とします。 [漢語大字典799頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=799)・[異體字字典](https://dict.variants.moe.edu.tw/dictView.jsp?ID=57018) |
| 𡷦（`U+2F87D`） | 𡷦（`U+21DE6`） | 岊 | 『漢語大字典』『異體字字典』は𡷦を岊と同字とします。『說文解字』が示す山と卪の構成を採用しました。 [漢語大字典802頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=802)・[異體字字典](https://dict.variants.moe.edu.tw/dictView.jsp?ID=56952&q=1) |
| 嵮（`U+2F87E`） | 嵮（`U+5D6E`） | 巓 | 『漢語大字典』は山頂の義で嵮を巔と同字とします。一点明朝正字では巓と巔の輪郭が同じです。 [漢語大字典817頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=817) |
| 𦇚（`U+2F898`） | 𦇚（`U+261DA`） | 彝 | 『漢語大字典』は𦇚を彝の古文とし、『異體字字典』も𦇚と𦇚を同じ見出しの異体に挙げます。 [漢語大字典1033頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=1033)・[異體字字典](https://dict.variants.moe.edu.tw/dictView.jsp?ID=14002&powerMode=2&q=1) |
| 𣏃（`U+2F8DD`） | 𣏃（`U+233C3`） | 支 | 『漢語大字典』は𣏃を支と同字とします。支は手を表す又を含みます。 [漢語大字典1244頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=1244) |
| 𣑭（`U+2F8E3`） | 𣑭（`U+2346D`） | 柵 | 『異體字字典』は𣑭を柵の異体とします。檢校表の柵では、木偏の右に横画が一本の冊を置きます。 [異體字字典](https://dict.variants.moe.edu.tw/dictView.jsp?ID=20885&la=0) |
| 𣫺（`U+2F8F9`） | 𣫺（`U+23AFA`） | 育 | 『漢語大字典』所引の『玉篇』は𣫺を育と同字とします。『說文解字』が示す𠫓と肉の構成を採用しました。 [漢語大字典2551頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=2551) |
| 𤉣（`U+2F91D`） | 𤉣（`U+24263`） | 災 | 『集韻』は𤉣を災と同字とします。 [字書の該当項](https://ctext.org/dictionary.pl?if=gb&char=𤉣) |
| 𤎫（`U+2F91F`） | 𤎫（`U+243AB`） | 光 | 『漢語大字典』は𤎫を光の古字とします。『說文解字』が示す、人の上に火を置く構成を採用しました。 [漢語大字典2397頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=2397) |
| 𤘈（`U+2F923`） | 𤘈（`U+24608`） | 牙 | 『漢語大字典』は牙の下に臼を置く𤘈を牙と同字とします。 [漢語大字典1499頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=1499) |
| 𤠔（`U+2F927`） | 𤠔（`U+24814`） | 猿 | 『康熙字典』所引の『字彙』は𤠔を猿の俗字とします。犬偏と袁を含む猿を採用しました。 [字書の該当項](https://ctext.org/dictionary.pl?if=gb&char=𤠔) |
| 㺬（`U+2F92A`） | 㺬（`U+3EAC`） | 珙 | 『漢語大字典』は玉器の義で㺬を珙と同字とします。玉偏と共を含む珙を採用しました。 [漢語大字典1179頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=1179) |
| 㼛（`U+2F933`） | 㼛（`U+3F1B`） | 鈃 | 『漢語大字典』は酒器の義で㼛を鈃と同字とします。金と幵を含む鈃を採用しました。 [漢語大字典1523頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=1523) |
| 𤰶（`U+2F935`） | 𤰶（`U+24C36`） | 申 | 『漢語大字典』所引の『玉篇』は𤰶を申の古文とします。 [漢語大字典2712頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=2712) |
| 𤾡（`U+2F93B`） | 𤾡（`U+24FA1`） | 蘤 | 『漢語大字典』所引の『龍龕手鑑』は花の義で𤾡を蘤と同字とします。 [漢語大字典2838頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=2838) |
| 𤾸（`U+2F93C`） | 𤾸（`U+24FB8`） | 蘤 | 『漢語大字典』『異體字字典』は𤾸を花の義の蘤に結び付けます。 [漢語大字典2839頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=2839)・[異體字字典](https://dict.variants.moe.edu.tw/dictView.jsp?ID=114605&powerMode=2) |
| 𥃲（`U+2F942`） | 𥃲（`U+250F2`） | 具 | 『漢語大字典』は𥃲を具の異体とします。下部が両手を表す具を採用しました。 [漢語大字典2642頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=2642) |
| 𥄙（`U+2F943`） | 𥄙（`U+25119`） | 視 | 『漢語大字典』は目と示を並べる𥄙を視の異体とします。一点明朝正字の視が採る示と見の字形を採用しました。 [漢語大字典2646頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=2646) |
| 𥄳（`U+2F944`） | 𥄳（`U+25133`） | 眔 | 『漢語大字典』所引の『正字通』は𥄳の本字を眔とします。 [漢語大字典3111頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=3111) |
| 䂖（`U+2F94C`） | 䂖（`U+4096`） | 石 | 『漢語大字典』は点のある䂖を石の異体とします。 [漢語大字典2586頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=2586) |
| 𥘦（`U+2F952`） | 𥘦（`U+25626`） | 赦 | 『漢語大字典』は示と攵を含む𥘦を赦の異体とします。赤と攵を含む赦を採用しました。 [漢語大字典1556頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=1556) |
| 𥥼（`U+2F95C`） | 𥥼（`U+2597C`） | 爵 | 『漢語大字典』は𥥼を酒器を表す爵の古文の楷書形とします。 [漢語大字典2921頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=2921) |
| 䊠（`U+2F967`） | 䊠（`U+42A0`） | 餼 | 『漢語大字典』は贈る穀物の義で䊠を餼と同字とします。 [漢語大字典3363頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=3363) |
| 糣（`U+2F969`） | 糣（`U+7CE3`） | 糝 | 『漢語大字典』は米を原料とする食品の義で、糣を糝と同字とします。 [漢語大字典3369頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=3369) |
| 𥾆（`U+2F96B`） | 𥾆（`U+25F86`） | 糾 | 『漢語大字典』は右の部品を省いた𥾆を糾の異体とします。糸と丩を含む糾を採用しました。 [漢語大字典3583頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=3583) |
| 縂（`U+2F96F`） | 縂（`U+7E02`） | 總 | 『漢語大字典』は縂を總の異体とします。糸と悤を含む總を採用しました。 [漢語大字典3658頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=3658) |
| 𦈨（`U+2F972`） | 𦈨（`U+26228`） | 鈃 | 『漢語大字典』は酒器の義で𦈨を鈃と同字とします。金と幵を含む鈃を採用しました。 [漢語大字典3132頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=3132) |
| 𦉇（`U+2F973`） | 𦉇（`U+26247`） | 缾 | 『漢語大字典』所引の『字彙補』は𦉇を缾と同字とします。 [漢語大字典3134頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=3134) |
| 𦋙（`U+2F975`） | 𦋙（`U+262D9`） | 罨 | 『異體字字典』は𦋙を罨の異体とします。『說文解字』に基づく網と奄の構成を採用しました。 [異體字字典](https://dict.variants.moe.edu.tw/dictView.jsp?ID=67201&la=0) |
| 𦌾（`U+2F977`） | 𦌾（`U+2633E`） | 罥 | 『漢語大字典』は𦌾を罥と同字とし、徐鍇『說文解字繫傳』が当時の表記とした罥を挙げます。 [漢語大字典3126頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=3126) |
| 𦓚（`U+2F97B`） | 𦓚（`U+264DA`） | 端 | 『漢語大字典』所引の『正字通』は𦓚を端の篆書の形とします。 [漢語大字典3005頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=3005) |
| 𦞧（`U+2F987`） | 𦞧（`U+267A7`） | 瘤 | 『康熙字典』所引の『字彙』は𦞧を瘤と同字とします。疒と留を含む瘤を採用しました。 [字書の該当項](https://ctext.org/dictionary.pl?if=gb&char=𦞧) |
| 劳（`U+2F992`） | 劳（`U+52B3`） | 勞 | 『異體字字典』は劳を勞の俗字とします。 [異體字字典](https://dict.variants.moe.edu.tw/dictView.jsp?ID=4293&la=0&powerMode=2) |
| 𦬼（`U+2F997`） | 𦬼（`U+26B3C`） | 薾 | 『漢語大字典』は𦬼を疲労の義の苶の古字に挙げ、『異體字字典』は花が盛んな義の薾にも結び付けます。一点明朝正字は苶に薾の字形を割り当てます。 [漢語大字典3405頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=3405) |
| 𦳕（`U+2F9A6`） | 𦳕（`U+26CD5`） | 草 | 『漢語大字典』は草の下に画を足した𦳕を草の異体とします。 [漢語大字典3461頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=3461) |
| 𧏊（`U+2F9AB`） | 𧏊（`U+273CA`） | 莔 | 『異體字字典』は𧏊を貝母を表す莔の異体とします。『說文解字』が示す艸と明の省形を含む莔を採用しました。 [異體字字典](https://dict.variants.moe.edu.tw/dictView.jsp?ID=68490) |
| 𦼬（`U+2F9AD`） | 𦼬（`U+26F2C`） | 菹 | 『漢語大字典』は野菜の漬物の義で𦼬を菹と同字とします。 [漢語大字典3527頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=3527) |
| 䕫（`U+2F9B2`） | 䕫（`U+456B`） | 夔 | 『康熙字典』所引の『正字通』は䕫の草冠を訛りとします。一点明朝正字の夔の選定形を採用しました。 [字書の該当項](https://ctext.org/dictionary.pl?if=gb&char=䕫) |
| 㒻（`U+2F9CA`） | 㒻（`U+34BB`） | 冒 | 『漢語大字典』は㒻を冒と同字とします。檢校表に基づき、冃と目を含む冒を採用しました。 [漢語大字典1621頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=1621) |
| 𧢮（`U+2F9CB`） | 𧢮（`U+278AE`） | 䚕 | 『漢語大字典』は見る・求める義で𧢮を䚕と同字とします。『說文解字』が示す見と声符の麗を含む䚕を採用しました。 [漢語大字典3922頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=3922) |
| 𨗒（`U+2F9E0`） | 𨗒（`U+285D2`） | 霆 | 『漢語大字典』は雷の義で𨗒を霆と同字とします。『說文解字』が示す雨と声符の廷を含む霆を採用しました。 [漢語大字典4330頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=4330) |
| 𨗭（`U+2F9E1`） | 𨗭（`U+285ED`） | 遺 | 『漢語大字典』は𨗭を遺の異体とします。旁に貴を含む遺を採用しました。 [漢語大字典4141頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=4141) |
| 𨯺（`U+2F9ED`） | 𨯺（`U+28BFA`） | 鏢 | 『漢語大字典』は𨯺を鏢の訛字とします。金と票を含む鏢を採用しました。 [漢語大字典4605頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=4605) |
| 𨵷（`U+2F9F1`） | 𨵷（`U+28D77`） | 閶 | 『漢語大字典』は𨵷を閶と同字とします。門の内側に昌を置く閶を採用しました。 [漢語大字典4386頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=4386) |
| 𩅅（`U+2F9F6`） | 𩅅（`U+29145`） | 霶 | 『漢語大字典』所引の『龍龕手鑑』は、大雨の義で𩅅を霶の俗字とします。 [漢語大字典4338頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=4338) |
| 𩐊（`U+2F9FB`） | 𩐊（`U+2940A`） | 齏 | 『漢語大字典』は𩐊を齏と同字とし、『正字通』も齏を本字とします。 [漢語大字典4694頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=4694) |
| 䪲（`U+2F9FC`） | 䪲（`U+4AB2`） | 髡 | 『漢語大字典』は剃髪の義で䪲を髡と同字とします。『說文解字』が示す髟と声符の兀を含む髡を採用しました。 [漢語大字典4644頁](https://ivantsoi.myds.me/web/hydzd/orgpage.html?page=4644) |

## 字の幅を調整した3件

次の3件は、正準対応先である「書」または「者」と同じ字形を表示します。両字とも「日」の幅などを調整したため、一点明朝正字の字形とは差があります。 [調整箇所の一覧](glyph-differences.md#字の幅や配置を調整した字)

| 入力字 | 正準対応先と共用する字形 |
| --- | --- |
| 者（`U+FAB2`） | 者（`U+8005`） |
| 書（`U+2F8CC`） | 書（`U+66F8`） |
| 者（`U+2F97A`） | 者（`U+8005`） |
