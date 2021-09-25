# 書籍「最短コースでわかる PyTorch &深層学習プログラミング」サポートサイト

<div align="left">
<img src="images/hyoshi.png" width="200">
</div>

　当サイトは、書籍「最短コースでわかる PyTorch &深層学習プログラミング」のサポートサイトです。  

## 実習Notebookリンク
　本書の実習コードは、Google Colabで動かすことを前提に、すべてGithub(当サポートサイト)で公開しています。  

[実習Notebook一覧](notebooks.md)

[実習Notebookの動かし方](refs/how-to-run.md)



## Amazonへのリンク
[単行本](https://www.amazon.co.jp/dp/4296110322) 
 
[Kindle](https://www.amazon.co.jp/dp/B09G622WB6/)  

　
## 内容紹介
　人気のAIフレームワーク「PyTorch」で、ディープラーニングプログラミングができるようになる本です。ディープラーニングのアルゴリズムが原理からわかります。初心者でも他書に頼らず、本書1冊でマスターできます！

本書は、次のような読者を想定しています。

1. **企業でディープラーニングプログラムを業務で利用している、あるいはこれから利用しようとしているITエンジニアや研究者**  
　Keras/Tensorflowを使った経験がある方は、まずPyTorch独特の「ポリシー」につまずきがちです。PyTorchは「多値分類モデルにおける損失関数」の考え方が独特で、それを分かりやすく解説します。

2. **入門書を読んで機械学習やディープラーニングアルゴリズムの実装イメー ジは持てたが、この先どのように活用したらよいかがわからない方**  
　9 ~ 12 章の「画像認識 実践編」では、最終的に「転移学習」と呼ばれる少ない学習データで学習可能な方法を用いて、自分で集めた画像データを使って 分類モデルを作ります。12 章までたどり着けば、すぐに自分で集めた画像デー タを使って分類モデルが作れるようになります。
 また、8 章までの内容は PyTorch でのプログラミング方法を理解すると同時 に、これまで入門書で学んだ機械学習やディープラーニングのアルゴリズムを 復習することにもなります。

3. **理工系の大学・大学院の学生で研究の一環としてディープラーニングのプログラムを開発する必要がある方**  
　今後、論文で公開されている実装コードを試すには、PyTorchの知識が必須になってきます。本書では、ディープラーニングに必要な数学をイメージとして解説するので、公開コードを深く理解し、応用できるようになります。

4. **まだPythonもKeras/TensorFlowも知らないが、ディープラーニングプログラミングをこれから勉強してみたいという方**  
　初心者に向けて、PyTorchプログラミングを理解するのに必要な、Pythonの基本文法と、NumPy、Matplotlibの必要最小限の機能を、巻末の講座として用意しました。目的がディープラーニングだけなら、本書の講座で書いた概念・機能だけを理解すれば十分で、ディープラーニングを学ぶためのスタートラインに立てます。

　本書は、新しい概念は一気には詰め込まず、できるだけ細分化して一歩一歩確実に進めます。機械学習の基本から、「CNN」などを使った画像認識ディープラーニングモデルの開発・チューニングまでをじっくり学べます。


## 目次

* 序章    初めての画像認識

### 基礎編  
* 1章     ディープラーニングのためのPythonのツボ
* 2章     PyTorch入門
* 3章     初めての機械学習
* 4章     予測関数の定義

### 機械学習 実践編 
* 5章     線形回帰
* 6章     2値分類
* 7章     多値分類
* 8章     MNISTを使った数字認識

### 画像認識 実践編 
* 9章     CNNによる画像認識
* 10章    チューニング技法
* 11章    学習済みモデルの利用
* 12章    カスタムデータによる画像認識

### 講座　
* Python入門
* NumPy入門
* Matplotlib入門

## 本書の特徴

### 勾配降下法の動作原理とPyTorch実装を、イメージから理解
　ディープラーニングの学習原理である勾配降下法は、3章で山登りのたとえ話で数式なしに理解できるようになります。アルゴリズムとしての動作原理と、PyTorch実装については、下の2つの図で、より具体的なイメージが持てます。

**勾配降下法の動作原理**
<div align="left">
<img src="images/fig01.png" width="500">
</div>
</br></br>

**PyTorchによる勾配降下法実装**
<div align="left">
<img src="images/fig02.png" width="500">
</div>

### 重要概念を一歩一歩確実に理解
　PyTorchプログラミングにおいて重要な概念については、詰め込まず、一歩一歩確実に進めるようにしてあります。見開きのコースマップで、どこまで進んだかも一目でわかります。

**コースマップ**
<div align="left">
<img src="images/fig03.png" width="600">
</div>


### 合成関数も可視化ツールで理解
　機械学習・ディープラーニングにおける学習とは、「損失」と呼ばれる合成関数の最適化です。本書では、PyTorchが自動生成した合成関数（計算グラフ）を可視化するツールを活用して、この合成関数の様子をイメージから理解できるようにしています。

**計算グラフの可視化例**
<div align="left">
<img src="images/fig04.png" width="500">
</div>



## 正誤訂正・FAQ

<!---
* [Notebook補足情報](notebook-ref.md)
-->  

* [正誤訂正](refs/errors.md)

* [FAQ](refs/faqs.md)


## その他解説記事

* [ONNXファイルへのエクスポート方法](refs/onnx.md)  
11章のコラム「**汎用性のある事前学習済みモデルの作り方**」で言及している手順はこのリンク先にあります。


## リンク集

|ソース  |タイトルとリンク  |補足|
|---|---|---|
|Amazon|[Amazonレビュー](https://www.amazon.co.jp/product-reviews/4296110322)||
|Honto|[Honto](https://honto.jp/netstore/pd-book_31207319.html)||
|読書メーター|[読書メーター](https://bookmeter.com/books/18544605)||
|BookLive|[BookLive](https://booklive.jp/product/index/title_id/1014297/vol_no/001)||
|twitter|[@makaishi2](https://twitter.com/makaishi2)|著者は原則twitterではつぶやきませんが、書籍に関連したつぶやきをretweetで紹介しています。|
|IBM Blog|[AI関連書籍三冊目を出版したIBM赤石雅典に聞く「AIと仕事と執筆」](https://www.ibm.com/blogs/solutions/jp-ja/data_science_and_ai_akaishi-san/)|IBM勤務時代、会社のブログにインタビュー記事が紹介されています。|
|からあげ様ブログ|[PyTorch入門書の決定版！「最短コースでわかる PyTorch ＆深層学習プログラミング」](https://karaage.hatenadiary.jp/entry/2021/09/24/073000)|AI関連で有名なブロガーである「からあげ」様による書評です。|

***
