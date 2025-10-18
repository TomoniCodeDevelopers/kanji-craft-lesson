```package
github:TomoniCodeDevelopers/kanji-craft#v1.0.1
```

# @explicitHints true
# @flyoutOnly true

# 漢字クラフト（エージェントで書いてみよう）


## ステップ1
### ブロックをおく
エージェントが文字を書きはじめる場所をえらぶブロックを **「エージェント」** の中からえらびます。

<img src="https://raw.githubusercontent.com/TomoniCodeDevelopers/kanji-craft-lesson/main/docs/img2.png" higth="200">

つぎに、ツールボックスから **「漢字クラフト」** をクリック。  
そこにあるブロックをもってきて、ブロックをつなげる。

<img src="https://raw.githubusercontent.com/TomoniCodeDevelopers/kanji-craft-lesson/main/docs/img1.png" higth="200">

すべてつなげるとこんな感じになります。

<img src="https://raw.githubusercontent.com/TomoniCodeDevelopers/kanji-craft-lesson/main/docs/img3.png" higth="500">

## ステップ2
### Webツールから変換
「[漢字クラフト Webツール](https://TomoniCodeDevelopers.github.io/kanji-craft-lesson/)」を開きます。  

文字を入力すると、**16進数コード** の書き方に変わります。  

Minecraftに戻ってきて、
*「エージェントに...」** ブロックの、(" ")になっている場所に、
**16進数コード** をそのまま入れます。 

例：  
16x16:なんとかかんとか



## ステップ3
### 実行
エージェントに文字を書いてもらう向きを「床」「壁」どちらかえらんで、
原点の位置を決めて実行すると、エージェントが一つずつブロックを置いて漢字を描いてくれます。  


## ステップ4
### ストラクチャーブロックを使ってみよう
ストラクチャーブロックを右クリックし、設定を開きます。
モードを「3Dエクスポート」にして、サイズを指定していきます。

「サイズ」のX,Y,Zでそれぞれ縦横のブロック数を決めて、
「オフセット」のX,Y,Zで範囲をストラクチャーブロックからずらしたりできます。

範囲が指定できたら「エクスポート」ボタンをクリックすると、「GLBファイル(マイストラクチャーブロック.glb)」というファイルが保存できます。

### 3Dデータに変換
保存が完了したら、
「[3Dデータ変換Webツール](https://tomonicodedevelopers.github.io/kanji-craft-lesson/glb2stl.html)」を開きます。  

左上の「ファイルを選択」ボタンをクリックして、さっき保存したGLBファイル(マイストラクチャーブロック.glb)を読み込みます。
そのあと、「読み込んでプレビュー」ボタンをクリックすると、保存した3Dデータが読み込まれるはずです。

問題なければ、「STLを書き出し」ボタンをクリックすると、3Dプリンターで印刷するときに使うファイルがダウンロードできます。









