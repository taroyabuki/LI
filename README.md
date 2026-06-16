# 情報リテラシ

**♠が付いている項目は必須ではない．**

## ガイダンス

### 教科書

- 矢吹太朗『Webのしくみ』（サイエンス社, 2020） [サポートサイト](https://github.com/taroyabuki/webbook)

### スケジュール

講義は次の要素で構成される．

- 解説
- 小テスト
- 演習

|回|日付|講義|小テストの範囲|演習|提出物|
|-:|--|--|--|--|:-:|
|1|4/14|教科書第0章|無|無（宿題有）|無|
|2|4/21|教科書第1章|第0章，第1回の講義|GitHub Pages|有|
|3|4/28|教科書第2章|第1章，第2回の講義|リンク|有|
|4|5/12|教科書第3章|第2章，第3回の講義|画像|有|
|5|5/19|教科書第4章|第3章，第4回の講義|箇条書き|有|
|6|5/26|教科書第5章|第4章，第5回の講義|表|有|
|7|6/2|教科書第6章|第5章，第6回の講義|CCライセンス|有|
|8|6/9|教科書第7章|第6章，第7回の講義|CSS|有|
|9|6/16|教科書第8章|第7章，第8回の講義|暗号|有|
|10|6/22|教科書第9章|第8章，第9回の講義|構文チェック|有|
|11|6/30|教科書第10章|第9章，第10回の講義|データベース|有|
|12|7/7|教科書第11章|第10章，第11回の講義|ボックスモデル|有|
|13|7/14|教科書第12章|第11章，第12回の講義|フォント|有|

### 成績

- 小テスト（12回50点）
- 演習提出物（12回50点）

### その他

- 自分だけの質問はmanabaの「個別指導(コレクション)」でする．
- 全員が関係しそうな質問はmanabaの「スレッド」でする．

## 第1回

1. 教科書第0章「この本の読み方」 [補足資料](https://github.com/taroyabuki/webbook/blob/master/chapters/00.md)
1. 宿題の確認

### 宿題

- https://github.com/ でアカウントを作成する．すでにアカウントを持っている人はそれを使ってよい．
    1. 大学のメールアドレス（chibatech.ac.jp）を登録する．
    1. 確認のメールが届いたら，対応する．
    1. GitHubではブラウザの自動翻訳をオフにする．（「commit」が「責任を負わせる」になるのは困る．）
    1. ♠卒業後使えなくなることに備えて，別のメールアドレスも登録しておくとよい．右上のアイコン→Settings→Emails→Add email address
- ♠図書館の本を検索する方法を確認する．
    - [図書館](https://chibatech.jp/about/library/)のOPAC
    - ♠[カーリル](https://calil.jp)
    - ♠Amazon＋ブラウザ拡張機能（例：Calilay）
- ♠[国立国会図書館デジタルコレクション](https://dl.ndl.go.jp/)の利用者登録をする．図書館に無い，高価な古書が読めることがある．例：[後藤憲一 著『現代科学における数学概説』（共立出版, 1981）](https://dl.ndl.go.jp/pid/12608596) 参考：[アマゾン](https://www.amazon.co.jp/dp/4320012984/)

## 第2回

1. 教科書第1章「ハイパーメディア」 [補足資料](https://github.com/taroyabuki/webbook/blob/master/chapters/01.md)
1. 小テスト
1. 演習

### 演習

**演習では，他人のデバイスに触らない．自分のデバイスを，他人に触らせない．**

1. GitHub のリポジトリを作成する．
    - Repository name：`literacy`
    - Add README: On
1. 自分のリポジトリのURLを確認する：`https://github.com/ユーザ名/literacy`
1. GitHub Pages を有効にする．
    1. Settings → Pages
    1. Branch のところで，main，/ (root) を選んで Save
    1. しばらくすると有効になる．設定画面を Ctrl-r でリロードすると，「Your site is live at https://ユーザ名.github.io/literacy/」が現れる．そこにアクセスできれば完了

GitHub Pages の URL：`https://ユーザ名.github.io/literacy/` を manaba のアンケートで報告する．ユーザ名を自分のもので置き換えて，ちゃんとアクセスできることを確認してから報告すること（期限あり）．**注意：報告するのはリポジトリのURL https://github.com/ユーザ名/literacy ではない！**

#### 重要なURL

- GitHubのリポジトリ（ファイル置き場）：https://github.com/●●●/literacy
- GitHub Pages（公開用ウェブサイト）：https://●●●.github.io/literacy/

## 第3回

1. 教科書第2章「検索」 [補足資料](https://github.com/taroyabuki/webbook/blob/master/chapters/02.md)
1. 小テスト
1. 演習

### 演習

**演習では，他人のデバイスに触らない．自分のデバイスを，他人に触らせない．**

#### 重要なURL

- GitHubのリポジトリ（ファイル置き場）：https://github.com/●●●/literacy
- GitHub Pages（公開用ウェブサイト）：https://●●●.github.io/literacy/

#### 作業

1. GitHubの自分のリポジトリ `literacy` に，ファイル link.html を追加する．内容は次のとおり．●と○の部分は自分で決めること．

```html
<a href="●">○</a>
```

2. Commit して少し待つと，GitHub Pages で ページが公開される．その URL は`https://ユーザ名.github.io/literacy/link.htrml` である．
3. 実際にページが閲覧できること，リンクをクリックして意図したページに遷移できることを確認する．

GitHub Pages の URL：`https://ユーザ名.github.io/literacy/link.html` を manaba のアンケートで報告する．

## 第4回

1. 教科書第3章「自分のメディア」 [補足資料](https://github.com/taroyabuki/webbook/blob/master/chapters/03.md)
1. 小テスト
1. 演習

マークアップに使う文字列自体を使いたいときは？　参照：教科書12.2.5項

♠次の二つを比較せよ．

- [HTMLのソース](https://github.com/taroyabuki/taroyabuki.github.io/blob/master/docs/quine.html)
- [ブラウザでの表示](https://taroyabuki.github.io/docs/quine.html)

### 演習

**演習では，他人のデバイスに触らない．自分のデバイスを，他人に触らせない．**

#### 重要なURL

- GitHubのリポジトリ（ファイル置き場）：https://github.com/●●●/literacy
- GitHub Pages（公開用ウェブサイト）：https://●●●.github.io/literacy/

#### 準備

HTML ファイルを書く環境を整える．

1. ファイルの拡張子が表示されるように，エクスプローラを設定する．
1. VS Code をインストールする．
    - Microsoft Store で「vscode」を検索して Visual Studio Code を見つけてインストールする．
    - あるいは，スタートボタンを右クリック→ターミナルで「`winget install Microsoft.VisualStudioCode`」を実行する．
    - あるいは，https://code.visualstudio.com からインストーラをダウンロードして実行する．♠インストール時に他ではしづらい設定ができる．
1. VS Code の拡張機能「Live Preview」をインストールする．
1. （オプション）VS Code の拡張機能「Japanese Language Pack for Visual Studio Code」をインストールして，UI（ユーザインタフェース）を日本語化する．

#### 本題

1. 作業用のフォルダ（例：デスクトップ/literacy）を作る．
2. AI で画像を作り，デスクトップ/literacy/image.png あるいは image.jpg に保存する．
3. VS Code で次のようなファイルを新規作成し，デスクトップ/literacy/image.html に保存する．（src 属性値をファイル名に合わせる．）

```html
<p>画像の生成に使ったプロンプト</p>
<img src="image.png" alt="生成された画像">
```

4. Live Preview で，画像が表示されることを確認する．
5. GitHub (https://github.com/●●●/literacy) に，image.html と image.png をアップロードする．（本当は，クローン・コミット・プッシュなのだが，ここでは割愛）
6. https://●●●.github.io/literacy/image.png で画像が表示されることを確認する．
7. https://●●●.github.io/literacy/image.html で画像を含むページが表示されることを確認する．
8. 次のURLを manaba のアンケートに入力する．●●●の部分を自分のユーザ名で置き換えて，ページにアクセスできること，画像が表示されること確認してから入力すること．

画像を含むページのURL　形式はhttps://●●●.github.io/literacy/image.html

## 第5回

1. AIについて
1. 教科書第4章「ライセンス」 [補足資料](https://github.com/taroyabuki/webbook/blob/master/chapters/04.md)
1. 小テスト
1. 演習

### 演習

**演習では，他人のデバイスに触らない．自分のデバイスを，他人に触らせない．**

#### 重要なURL

- GitHubのリポジトリ（ファイル置き場）：https://github.com/●●●/literacy
- GitHub Pages（公開用ウェブサイト）：https://●●●.github.io/literacy/

#### 作業

1. テキストエディタで空のテキストファイルlists.htmlを作成する．
1. 3種類の箇条書きを作成する．
1. GitHub (https://github.com/●●●/literacy) に，lists.htmlをアップロードする．（本当は，クローン・コミット・プッシュなのだが，ここでは割愛）
1. 次のURLをmanabaのアンケートに入力する．●●●の部分を自分のユーザ名で置き換えて，ページにアクセスできること，3種類の箇条書きが表示されることを確認してから入力すること．

ページのURL　形式はhttps://●●●.github.io/literacy/lists.html

## 第6回

1. 教科書第5章「シェア」 [補足資料](https://github.com/taroyabuki/webbook/blob/master/chapters/05.md)
1. 小テスト
1. 演習

### 演習

**演習では，他人のデバイスに触らない．自分のデバイスを，他人に触らせない．**

#### 重要なURL

- GitHubのリポジトリ（ファイル置き場）：https://github.com/●●●/literacy
- GitHub Pages（公開用ウェブサイト）：https://●●●.github.io/literacy/

#### 作業

1. テキストエディタで空のテキストファイルtable.htmlを作成する．
1. 表を作成する．
1. GitHub (https://github.com/●●●/literacy) に，table.htmlをアップロードする．（本当は，クローン・コミット・プッシュなのだが，ここでは割愛）
1. 次のURLをmanabaのアンケートに入力する．●●●の部分を自分のユーザ名で置き換えて，ページにアクセスできること，表が表示されることを確認してから入力すること．

ページのURL　形式はhttps://●●●.github.io/literacy/table.html

## 第7回

1. 教科書第6章「アカウント」 [補足資料](https://github.com/taroyabuki/webbook/blob/master/chapters/06.md)
1. 小テスト
1. 演習

### 演習

**演習では，他人のデバイスに触らない．自分のデバイスを，他人に触らせない．**

#### 重要なURL

- GitHubのリポジトリ（ファイル置き場）：https://github.com/●●●/literacy
- GitHub Pages（公開用ウェブサイト）：https://●●●.github.io/literacy/

#### 作業

画像を掲載する HTML ページを作り，ライセンスを明記する．

1. 自分で画像を用意する．第4回で作った画像を再利用してもよい（image.html を cc.html にコピー）．ライセンスを自分で与えられるもの（自分のもの）でなければならない．
2. 画像を表示する HTML 文書を作る．ファイル名は cc.html とする．
3. 画像のライセンスを明記する．そのための HTML を，https://creativecommons.org/chooser/ で作成し，img 要素の下に貼り付ける．HTML の全体は次のようになる．（Creator of work に本名を書いてもよいが，この課題のために本名をさらす必要はない．）

```html
<img src="画像ファイル名" alt="画像についての説明">
作成した HTML 要素
```

4. GitHub (https://github.com/●●●/literacy) に，cc.htmlをアップロードする．（本当は，クローン・コミット・プッシュなのだが，ここでは割愛）
5. 次のURLをmanabaのアンケートに入力する．●●●の部分を自分のユーザ名で置き換えて，ページにアクセスできること，画像が表示されること，ライセンスが表示されることを確認してから提出すること．

ページのURL　形式はhttps://●●●.github.io/literacy/cc.html

## 第8回

1. 教科書第7章「クラウド（crowd）」 [補足資料](https://github.com/taroyabuki/webbook/blob/master/chapters/07.md)
1. 小テスト
1. 演習

### 演習

**演習では，他人のデバイスに触らない．自分のデバイスを，他人に触らせない．**

#### 重要なURL

- GitHubのリポジトリ（ファイル置き場）：https://github.com/●●●/literacy
- GitHub Pages（公開用ウェブサイト）：https://●●●.github.io/literacy/

#### スタイルの適用方法

色を青にすることを例に，スタイルの適用方法を三つ示す．

- style属性：`<span style="color:blue;">対象</span>` とすると，対象が青になる．この方法は，自分で手で HTML を書くときは使わなくてよいが（後で変更するのが大変だから）．
- style要素：`<style>セレクタ {color:blue;}</style>` セレクタに該当する要素にスタイルを適用する．セレクタの書き方はいろいろあるが，要素名（例：`span`）を書くのが簡単である．
- styleファイル：`セレクタ {color:blue;}`のような内容のファイル（例：style.css）を作って，HTMLで`<link rel="stylesheet" href="style.css">`として指定する．この方法は，複数の HTML 文書に同じスタイルを適用したいときに使う．

この演習ではstyle要素を使う．

#### 作業

CSSを使って，文書のキーワードを青にする．

1. style.html を作る．内容は次の通り（教科書p.57の図3.3を参照）．

```html
<!DOCTYPE html>
<html lang="ja">

<head>
  <meta charset='utf-8' />
  <meta name="viewport" content="width=device-width" />
  <title>スタイル</title>
  <style>

  </style>
</head>

<body>
  <p>
  </p>
</body>

</html>
```

2. p要素の中に文章を書く（60文字程度）．
3. 文章中のキーワードをstrong要素で強調する．（おそらく太字になる．プレビューで確認せよ．）
4. style要素の中に `strong {color:blue;}` と書く．（指定したキーワードが青になる．プレビューで確認せよ．）
5. GitHub (https://github.com/●●●/literacy) に，style.htmlをアップロードする．（本当は，クローン・コミット・プッシュなのだが，ここでは割愛）
6. 次のURLをmanabaのアンケートに入力する．●●●の部分を自分のユーザ名で置き換えて，ページにアクセスできること，キーワードが青になっていることを確認してから提出すること．

ページのURL　形式はhttps://●●●.github.io/literacy/style.html

## 第9回

1. 教科書第8章「暗号」 [補足資料](https://github.com/taroyabuki/webbook/blob/master/chapters/08.md)
1. 小テスト
1. 演習

### 演習

**演習では，他人のデバイスに触らない．自分のデバイスを，他人に触らせない．**

#### 重要なURL

- GitHubのリポジトリ（ファイル置き場）：https://github.com/●●●/literacy
- GitHub Pages（公開用ウェブサイト）：https://●●●.github.io/literacy/

#### Google Colabのヒント

- Google Colabでは，コードセルのコードをCtrl+Enterで実行する．
- 「+ コード」でコードセル，「+ テキスト」でテキストセルを追加する．
- テキストファイルの作成方法：コードセルで，`!printf "内容" > ファイル名` を実行する．ファイルがWebで公開されている場合は，コードセルで`!wget URL` で取得する．
- テキストファイルの確認方法：コードセルで，`!cat ファイル名` を実行する．

#### 課題：メッセージの暗号化

- [演習用資料](https://colab.research.google.com/github/taroyabuki/webbook/blob/master/chapters/08_cipher.ipynb)
- 課題で用いる矢吹の公開鍵：https://raw.githubusercontent.com/taroyabuki/LI/refs/heads/main/yabuki-public.pem

講義用資料を参考に，矢吹だけが読める暗号ファイル report-secret を作成し，GitHub で公開する．

1. テキストファイル report を作成する．内容は自分の学籍番号．ASCII 文字（いわゆる半角英数字）のみを使うこと．
1. 矢吹の公開鍵を使って，report を暗号化する．暗号化されたファイルの名前は report-secret．（公開鍵はテキストファイルだから，上記のヒントの方法で作れる．暗号化は演習用資料の方法で行う．ファイル名部分を置き換えればよい．）
1. report-secret を GitHub にアップロードする．（Colab からダウンロードして，GitHub にアップロードするのが簡単．ダウンドードは，Colab上で，ファイルの右の「・・・」を縦にしたアイコンをクリックして行う．）
1. https://●●●.github.io/literacy/report-secret で暗号化されたファイルにアクセスできることを確認する（内容は読めない）．
1. 次のURLをmanabaのアンケートに入力する．●●●の部分を自分のユーザ名で置き換えて，ページにアクセスできることを確認してから提出すること．

ページのURL　形式はhttps://●●●.github.io/literacy/report-secret

ヒント

- 演習用の資料の「#(4.2) ボブの公開鍵を使って暗号文を作る」を，ファイル名を置き換えて実行する．
- 作成した暗号ファイル report-secret を読めるのは，秘密鍵を持つ矢吹だけだから，正しく暗号化できたかどうかは自分では確認できない．手順の正しさを確信したい場合は，自分で公開鍵と秘密鍵を作り，ファイルを公開鍵で暗号化し，秘密鍵で復号してみるとよいだろう．
