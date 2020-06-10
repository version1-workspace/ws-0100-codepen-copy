
# codepen-copy


デモ: https://version-1.github.io/ws-0100-codepen-copy/

HTML, CSS(SASS), SMACSSとレスポンシブコーディングを勉強するためのリポジトリです。
上記デモサイトをみながらなるべく同じサイトができるようにコーディングをしてもらいます。



## 課題で身に着けること

- 変更に強いCSS設計（SMACCSS)
- CSSのモジュール化
- レスポンシブデザイン
- sass記法
- sassの変数定義、mixinの使い方
- セマンティックな命名

## 課題の進め方

### 1. ドキュメント/記事を読んで必要な知識を理解する

#### SMACSSについて

リンク参照:
- [CSSスタイルガイドのSMACSSを勉強してみたまとめ](https://ver-1-0.net/2017/12/10/learn-smacss)
- [脱ビギナーのためのCSS入門](https://speakerdeck.com/jjoo/tuo-biginafalsetamefalsecssru-men)

公式ドキュメント:

English: http://smacss.com/ -> click "Download the Book!"

日本語: http://smacss.com/files/smacss-ja.pdf

#### レスポンシブデザインについて

- [【図解】レスポンシブデザインとは？定義、特徴、メリットとデメリットを解説](https://www.yamatofinancial.jp/learning/know-how/what-is-responsive-web-design.html)
- [レスポンシブデザインに必要不可欠なブレイクポイントとメディアクエリとは？](https://www.studio-umi.jp/blog/185/610)

#### Sassについて

- [sass公式](https://sass-lang.com/)
- [SASS](https://www.webdesignleaves.com/pr/css/css_basic_08.html)
- [【node-sass】 導入方法 - Qiita](https://qiita.com/Accio/items/2d0d0c3adc98e254571f)

node-sassはすでに導入済みですがコンパイルの仕組みなどを理解するために貼ってあります。

#### Npmについて

- [便利なパッケージ管理ツール！npmとは【初心者向け】](https://techacademy.jp/magazine/16105)

### 2. このリポジトリをフォーク

リポジトリ のフォークはGihubの画面右上のForkボタンから自分のアカウントにリポジトリ をコピーすることができます。

### 3. フォークしたリポジトリ をクローン

フォークしたリポジトリ を自分のローカル環境にクローンします。

### 4. クローンしたファイルの中身を確認して課題を開始
```
cd ws-0100-codepen-copy
npm install
npm run compile // sassの変更を検知してコンパイルするnodeサーバを起動
```

nodeサーバが起動している間は、sassの変更が自動で反映されるようになっています。
また使用するHTMLファイルはindex.htmlだけでその他必要なsassファイルはすでに配置済みです。
1.で読んだSMACSSのドキュメントを元にどのようにファイルが分割されて配置されているか意識しながら、
所定の場所に必要なスタイルを付けたして行ってください。

いきなり全部をやろうとすると処理が難しくなるので、自分で理解できる範囲まで作業を分割してコーディングを進めてください。


1. サイドバーのコーディング
2. ヘッダーのコーディング
3. コンテンツ部分のコーディング
4. フッター部分のコーディング


と順番を決めたら、
次はサイドバーの**「ロゴの部分をコーディングする」**という様に可能な限り作業を分割して実装を進められると効率よく実装が進められるかと思います。

作業を分割してどうしても実装できない、長時間詰まってしまう部分は後回しにしてできるところからやるようにしてください。

### 5. github pagesにてサイトを公開

作業が終わったら変更をコミット&pushしてリモートリポジトリ に変更を反映させます。
masterへの変更が終わったら下記手順でサイトをgithub ページ上に公開してください。

https://help.github.com/ja/github/working-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## 注意点

### FontAwesomeについて

雛形のhtmlでFontAwesomeというアイコンを表示できるライブラリを読み込んでいるので実装の時に使うアイコンはすべて、
こちらを使用してください。使用しているアイコンの名前や表示の仕方はデモサイト上でブラウザの検証ツールを使って確認してください。

参考記事: https://saruwakakun.com/html-css/basic/font-awesome

### Google Fontについて

無料で使えるフォントファイルライブラリのGoogleFontもデフォルトで読み込む様な設定をしています。
base.sassでフォントファミリーは指定しているので新たに自分でフォントファミリを指定する必要はありません。

### 画像について

実装の際に使用する画像はネット上で公開されている画像でも自分の好きな画像でも構いません。
レイアウトが崩れなければよいので、適当な画像を使用してください。

