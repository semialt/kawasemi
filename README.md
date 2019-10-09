# かわせみ配列
かわせみ配列は、覚えやすくて効率がいい、文字キー同時押し行段系かな配列です。

かわせみ配列では、５０音の行（かさたなはまら、その濁音と半濁音）を示すキーを左手で、段（あいうえおやゆよ）を示すキーを右手で同時押しすることによってかな文字を入力します。

左手の１２個の行指定キーと「わ」キー、右手の８個の段指定キーと「っ」「ん」「を」キーを覚えることで、濁音、拗音を含めた基本的なかな文字は全て入力できるようになっています。また、行指定キーと段指定キーは５０音表をある程度なぞって規則的に配置されており、ローマ字入力よりも覚えやすくなっています。

2019年8月時点で、実装が公開されているかな文字配列の中では、一番タッチタイピングが覚えやすい配列でしょう。

良く使う文字を中心とした２７のかな文字を、文字キーを単独で打つことによって入力できるようになっており、効率的な入力ができます。これらのかな文字のほとんどは、関連する行指定キーまたはその近くにまとめられており、自然と覚えられるように工夫されています。

さらに、拗音や撥音を１動作で、かつ覚えやすい配置で入力できるようにしてあり、これによりさらに入力効率が良くなっています。

## 行指定キーと段指定キー

標準的なQWERTYキーボードの並びを以下のように表現することとすると、

上段　ＱＷＥＲＴ　ＹＵＩＯＰ  
中段　ＡＳＤＦＫ　ＨＪＫＬ；  
下段　ＺＸＣＶＢ　ＮＭ，．／

かわせみ配列の行指定キーと段指定キーは以下のように並んでいます。

　　　行指定キー　段指定キー  
　　　小薬中人伸　伸人中薬小     
上段　　がざだば　　よゆや  
中段　なかさたは　えおういあ  
下段　　らま　ぱ

「行指定キー」の下にある「小薬中人伸」という表記は、それぞれの列のキーを打つときに使う指を表しています。「伸」というのは、「人差し指を伸ばして打つ」という意味です。
 
### あ行とや行の入力

あ行とや行の文字は、右手で、段指定キーを打つだけで入力できます。

つまり、

キー　→　カナ   
Ｊ　　→　お  
Ｉ　　→　ゆ  
；　　→　あ

といった具合です。

## かさたなはまら行の入力

あ行とや行（前述）とわ行（後述）以外の清音かなの入力には、右手で段指定キーを打つのにあわせて同時に左手で行指定キーを打ちます。

　　　行指定キー　段指定キー  
　　　小薬中人伸　伸人中薬小     
中段　なかさたは　えおういあ  
下段　　らま

キー　　→　カナ  
Ａ＋Ｊ　→　　の  
Ｇ＋Ｈ　→　　へ  
Ｃ＋Ｌ　→　　み

といった具合です。

### がざだばぱ行の入力

　　　行指定キー　段指定キー  
　　　小薬中人伸　伸人中薬小     
上段　　がざだば  
中段　　　　　　　えおういあ  
下段　　　　　ぱ　　　　　　  


濁音を入力するときは、左手で静音の行指定キーの一個上のキーを行指定キーとして打ちます。
ぱ行については、は行の下のキーを打ちます。

キー　　→　カナ  
Ｗ＋；　→　　が  
Ｒ＋Ｌ　→　　ぢ  
Ｂ＋Ｊ　→　　ぽ

といった具合です。

### 拗音の入力

　　　行指定キー　段指定キー  
　　　小薬中人伸　伸人中薬小     
上段　　がざだば　　よゆや  
中段　なかさたは  
下段　　らま　ぱ

「きゃ」「しゅ」「ちょ」などの拗音は左手で行指定キーを打ち、右手で上段の段指定キーを打ちます。

## 単打での省入力と「わ」「を」「っ」「ん」「、」「。」「ー」

　　　小薬中人伸　伸人中薬小     
上段　にがじでば　れよゆやを   
中段　のかしとは　えおういあ   
下段　なるまてわ　っん、。ー

は行指定キーの下のキー（人差し指の伸ばした列の下段）を単打すると「わ」、あ段指定キーの上（小指上段）を単打すると「を」が入力できます。わ行は２文字しかないので、わ行指定キーは設定していません。

「っ」「ん」「、」「。」「ー」の各文字は、右手下段を単打することで入力できます。

さら、各行指定キーを同時押しではなく、単打で打つと、その行の中で使用頻度が一番高いかなが入力できます。例外は「ぱ行」で「わ」が入力されるようにしています。これは、ぱ行の文字はどれも使用頻度が低いので、単打キーを割りあてるのがもったいなかったからです。

最後に、な行指定キーの下のキー（左手小指下段）の単打で「な」、た行指定キーの下のキー（左手人差指下段）の単打で「て」が入力できます。それぞれ比較的使用頻度が高く、同じ列の行指定キーにひも付けて覚えやすいかなを設定しています。

また、え段指定キーの上のキー（右手人差し指を伸ばした列の上段）の単打で「れ」が入力できます。これは、比較的押しにくいキーをえ段指定キーと同じ列に配置することで覚えやすい位置に置いています。

ここまででのキーの押し方を覚えれば、通常の日本語の文章は問題なく入力できるはずです。最初は行指定キーと段指定キーの同時押しを集中的に練習し、慣れてきたら、単打入力も使って楽をしていきましょう。

## 撥音拡張

　　　行指定キー　段指定キー  
　　　小薬中人伸　伸人中薬小     
上段　　がざだば  
中段　なかさたは　えおういあ  
下段　　らま　ぱ　ｴﾝｵﾝｳﾝｲﾝｱﾝ

左手で行指定キーを打ちながら、右手で「あ〜お」の段指定キーの下のキーを押すと、撥音を一発で入力できます。

キー　　→　カナ  
Ｄ＋，　→　すん  
Ｔ＋Ｎ　→　でん  
Ｃ＋／　→　まん

といった具合です。漢語の入力がぐっとスムーズになります。

## 記号の入力

左手で「Ｖ」のキー（た行指定キーの下のキー）を押し、同時に右手で各キーを押すことで、各種の記号を入力することができます。

　　　行指定キー  
　　　小薬中人伸　伸　人　中　薬　小     
上段　　　　　　　『』「」（）【】〈〉  
中段　　　　　　　　　・　…　／　《》  
下段　　　　☆　　　　，　．　　


## 小書き仮名の入力

左手で「Ｑ」のキー（な行指定キーの上のキー）を押し、同時に右手で各キーを押すことで、各種の小書きの仮名（捨て仮名）や旧かなを入力することができます。

　　　行指定キー　段指定キー  
　　　小薬中人伸　伸人中薬小     
数字段　　　　　　　　　ゐ  
上段　☆　　　　　ヶょゅゃゎ  
中段　　　　　　　ぇぉぅぃぁ  
下段　　　　　　　ゑ　、。ヵ

## 外来音の入力

左手で各行指定キーを押しながら、右手で「Ｙ」「Ｐ」「７」「８」「９」といったキーを押すことで各種の外来音を入力することができます。自分が多用する外来音でなければ、上記の「小書き仮名の入力」を使って２動作で入力する方が覚えやすいでしょう。打ちにくいパターンも多いので、無理して覚えて使う必要はありません。

- 「Ｙ」で「ぇ」を使った外来音を入力できます。Ｄ＋Ｙで「しぇ」、Ｔ＋Ｙで「う゛ぇ」など。
- 「Ｐ」で「ぁ」を使った外来音を入力できます。Ｇ＋Ｐで「ふぁ」、Ｔ＋Ｐで「う゛ぁ」など。
- 「７」で「ぉ」を使った外来音を入力できます。Ｆ＋７で「つぉ」、Ｇ＋７で「ふぉ」など。
- 「８」で「ぅ」や「ゅ」を使った外来音を入力できます。Ｆ＋８で「とぅ」、Ｇ＋８で「ふゅ」など。
- 「９」で「ぃ」を使った外来音を入力できます。Ｆ＋９で「てぃ」、Ｒ＋９で「でぃ」など。

## 設定ファイルと利用法

### DvorakJ

現在は、Windows用キーボード配列変更ソフトであるDvorakJ用の設定ファイルを公開しています。

まず、DvorakJをインストール後、DvorakJフォルダの中のdata\lang\jpn\同時に打鍵する配列\

に「かわせみ配列.txt」ファイルを置きます。

その上で、DvorakJの「日本語入力」「日本語入力用配列」「設定ファイル」で「かわせみ配列.txt」を選択すれば、かわせみ配列が使えるようになります。

この、「かわせみ配列.txt」は、GitHubのウェブサイトからコピー＆ペーストして、新しいファイルを作成するのが簡便です。ファイルをダウンロードした場合、「かわせみ配列.txt」文字コードの形式がBOMなしのUTF8となり、DvorakJが正しく認識することができません。「かわせみ配列.txt」をテキストエディタで開き、テキストの形式をBOM付きのUTF-8（改行コードはCRLF）に変更して再度保存する必要があります。


### かえうち

キーボード配列を変換するUSBアダプターの「かえうち」用の設定ファイルも以下のアドレスで公開しています。

https://kaeuchi.jp/forums/topic/%E3%81%8B%E3%82%8F%E3%81%9B%E3%81%BF%E9%85%8D%E5%88%97/#post-2995

## かわせみ配列改

３キー同時押しを行うため、キーボードによっては対応できない拡張を含んだ「かわせみ配列改.txt」のファイルも同梱しています。かわせみ配列との差分は、二重母音拡張のみです。

## 二重母音拡張

左手で行指定キーを押すのと同時に、右手で隣り合ったキーを同時に押すことで二重母音を簡単に入力することができます。

段指定キー  
　　　伸人　人中　中薬　薬小     
上段　ぇい　ょう　ゅう　いい  
中段　えい　おう　うう　あい  

「伸人」のキーは、右手の人差し指と中指をそれぞれキー１個分左に動かして打ちます。

左手でキーを打たず、右手だけで隣り合ったキーを同時に押すと、以下の文字が入力されます。

段指定キー  
　　　伸人　人中　中薬　薬小     
上段　　　　よう　ゆう　いい  
中段　えい　おう　うう　あい  

## その他の配列

### Special Thanks

かわせみ配列を作るにあたって、影響を受けた配列には以下のようなものがあります。

- こまどり配列、よだか配列：いずれも作者の自作の配列で、かわせみ配列の直系の祖先です。https://github.com/semialt/komadori https://github.com/semialt/yodaka
- つばめ配列：こまどり配列と続くよだか配列の派生元であり、作者が配列を自作する一番のきっかけとなった配列です。http://layout.kachoufuugetu.net/original/tsubame/
- AZIK：拗音拡張、撥音拡張の考え方はこの配列から学びました。http://hp.vector.co.jp/authors/VA002116/azik/azikinfo.htm
- 新下駄配列：文字キー同時打鍵によるかな入力はこの配列から学びました。https://kouy.exblog.jp/13627994/

### 思想の似た配列

かわせみ配列を作るときに参考にしたわけではありませんが、似た思想の配列として仕様が公開されているものとして、以下のようなものもあります。実装例はまだ無いようです。

- 50音行段入力：かわせみ配列よりもさらに50音表にそった規則性があります。「あ」は左手の担当で、単打拡張はすべて使用頻度によらず「あ段」となっています。撥音拡張等はないシンプルな構成になっています。http://oshiraseya.blog.fc2.com/blog-entry-8.html
- 新日本語入力方式（左右同時打鍵方式）：濁音を下段に配置していること、母音キーを押しっぱなしにした連続シフトができるようになっているのが特徴です。い～おの母音は単打では入力できないようです。撥音拡張はありませんが二重母音拡張を備えています。http://shouyouki.web.fc2.com/nyuuryoku.html
