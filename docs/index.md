---
var:
  header-title: "オンラインテキストテンプレート"
  header-date: "2024/04/23"
---

# 教育カリキュラム

## HTML (HyperText Markup Language)

- HTMLは、ウェブページの構造を定義するための<span class="masked">マークアップ言語</span>です。ウェブページの骨組みを作り、テキスト、画像、リンクなどの<span class="masked">コンテンツ</span>を配置するために使用されます。HTMLはタグと呼ばれる特定のキーワードを使用して、異なる要素を定義します。例えば、`<p>`タグは段落を、`<a>`タグはリンクを表します。
- 詳しい解説は[こちら](https://developer.mozilla.org/ja/docs/Learn/Getting_started_with_the_web/HTML_basics)

### HTMLの簡単な例

```html{.numberLines caption="example01.html"}
<!-- HTML5文書であることを宣言 -->
<!DOCTYPE html>
<!-- HTML文書の開始を示し、言語が英語であることを指定 -->
<html lang="ja">
  <!-- ヘッダー部分の開始 -->
<head>

    <!-- 文字エンコーディングがUTF-8であることを指定 -->
    <meta charset="UTF-8">

    <!-- ビューポートの設定を行い、レスポンシブデザインに対応 -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 

    <!-- ウェブページのタイトルを設定 -->
    <title>HTMLのタイトル</title>

<!-- ヘッダー部分の終了 -->
</head>

<!-- ボディ部分の開始 -->
<body>

    <!-- 見出しを設定 -->
    <h1>教材用サンプル</h1>

    <!-- 段落のテキストを追加 -->
    <p>こちらはテストで作成したWebページです。</p>

    <!-- リンクを設定 -->
    <a href="https://developer.mozilla.org/ja/docs/Learn/Getting_started_with_the_web/HTML_basics">HTMLとは</a>

    <!-- 画像を挿入 -->
    <img src="figs/computer_programming_man.png">

<!-- ボディ部分の終了 -->
</body>
<!-- HTML文書の終了 -->
</html>
```

<iframe src="index_html.html"></iframe>

## CSS (Cascading Style Sheets)

- CSSは、ウェブページのスタイルを定義するための<span class="masked">スタイルシート言語</span>です。HTMLで作成されたウェブページの見た目と感じを<span class="masked">カスタマイズ</span>するために使用されます。CSSを利用することで、色、フォント、レイアウトなどを制御し、ページ全体のデザインを向上させることができます。CSSは、HTML要素にスタイルルールを適用することで機能し、これにより開発者はページのプレゼンテーションを柔軟に管理できます。
- 詳しい解説は[こちら](https://developer.mozilla.org/ja/docs/Learn/Getting_started_with_the_web/CSS_basics)

```html{.numberLines caption="example02.html"}
<!-- HTML5文書であることを宣言 -->
<!DOCTYPE html>
<!-- HTML文書の開始を示し、言語が英語であることを指定 -->
<html lang="ja">
  <!-- ヘッダー部分の開始 -->
<head>

    <!-- 文字エンコーディングがUTF-8であることを指定 -->
    <meta charset="UTF-8">

    <!-- ビューポートの設定を行い、レスポンシブデザインに対応 -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 

    <!-- ウェブページのタイトルを設定 -->
    <title>HTMLのタイトル</title>

<!-- ヘッダー部分の終了 -->
</head>

<!-- ボディ部分の開始 -->
<body>

    <!-- 見出しを設定 -->
    <h1>教材用サンプル</h1>

    <!-- 段落のテキストを追加 -->
    <p>こちらはテストで作成したWebページです。</p>

    <!-- リンクを設定 -->
    <a href="https://developer.mozilla.org/ja/docs/Learn/Getting_started_with_the_web/HTML_basics">HTMLとは</a>

    <!-- 画像を挿入 -->
    <img src="figs/computer_programming_man.png">

<!-- ボディ部分の終了 -->
</body>
<!-- HTML文書の終了 -->
</html>
```

<iframe src="index_css.html"></iframe>

## JavaScript

- JavaScriptは、ウェブページにインタラクティビティを追加するためのプログラミング言語です。HTMLとCSSで構築された<span class="masked">静的</span>なページに動的な要素を加えることができます。例えば、ユーザーのアクションに応じてコンテンツを更新したり、APIからデータを取得して表示したりすることが可能です。JavaScriptはブラウザで直接実行され、ウェブページのユーザー体験を向上させるために広く利用されています。

```html{.numberLines caption="example03.html"}
<!-- HTML5文書であることを宣言 -->
<!DOCTYPE html>
<!-- HTML文書の開始を示し、言語が英語であることを指定 -->
<html lang="ja">
  <!-- ヘッダー部分の開始 -->
<head>

    <!-- 文字エンコーディングがUTF-8であることを指定 -->
    <meta charset="UTF-8">

    <!-- ビューポートの設定を行い、レスポンシブデザインに対応 -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 

    <!-- ウェブページのタイトルを設定 -->
    <title>HTMLのタイトル</title>

<!-- ヘッダー部分の終了 -->
</head>

<!-- ボディ部分の開始 -->
<body>

    <!-- 見出しを設定 -->
    <h1>教材用サンプル</h1>

    <!-- 段落のテキストを追加 -->
    <p>こちらはテストで作成したWebページです。</p>

    <!-- リンクを設定 -->
    <a href="https://developer.mozilla.org/ja/docs/Learn/Getting_started_with_the_web/HTML_basics">HTMLとは</a>

    <!-- 画像を挿入 -->
    <img src="figs/computer_programming_man.png">

<!-- ボディ部分の終了 -->
</body>
<!-- HTML文書の終了 -->
</html>
```

<iframe src="index_js.html"></iframe>

## 変数

### 役割

- 変数は、値を代入しておき、それを変更したときに動的に変わるようになります。
- プログラム内でデータを一時的に保持し、操作するために使用されます。これにより、プログラムはより動的で柔軟なデータ処理を実現できます。
- また、変数を使用することで、コードの再利用性が向上し、プログラムの可読性とメンテナンスが容易になります。

### コード例

```javascript{.numberLines caption="example01.js"}
let x = 10;

x = x + 5;

console.log(x);
```

このコードでは、`x`という変数に`10`を代入し、その後`x`に`5`を加えています。最終的に`x`の値は`15`となり、これが出力されます。

## 条件分岐

### 役割

- 条件分岐は、プログラム内で特定の条件を満たすかどうかに基づいて、異なるコードの実行パスを選択するために使用されます。
- これにより、プログラムはより柔軟に動作し、様々なシナリオに対応できるようになります。
- 例として、変数の値に基づいて異なるメッセージを表示することが挙げられます。

### コード例

```javascript{.numberLines caption="example02.js"}
let age = 20;

if (age >= 18) {

  console.log("成人です");

} else {

  console.log("未成年です");

}
```

このコードでは、`age`が`18`以上の場合は"成人です"を、そうでない場合は"未成年です"を出力します。

## 繰り返し処理

### 役割

- 繰り返し処理は、同じコードブロックを複数回実行するために使用されます。
- これにより、コードの冗長性を減らし、大量のデータ処理や反復的なタスクを効率的に処理することができます。
- 例として、変数の値を増加させながら一定の条件を満たすまでループを続けることが挙げられます。

### コード例

```javascript{.numberLines caption="example03.js"}
for (let i = 0; i < 5; i++) {

  console.log(i);

}
```

このコードでは、`0`から`4`までの数字が順番に出力されます。`for`ループによってそれぞれの値が`i`に代入され、出力されます。

## 例外処理

### 役割

- 例外処理は、プログラム実行中に発生する予期せぬエラーや例外に対処するために使用されます。
- これにより、プログラムの安定性と信頼性が向上し、エラーが発生しても適切に対応し、プログラムのクラッシュを防ぐことができます。
- 例として、ファイル読み込み時にファイルが存在しない場合にエラーメッセージを表示することが挙げられます。

### コード例

```javascript{.numberLines caption="example04.js"}
try {

  console.log(10 / 0);

} catch (error) {

  console.log("0で割ることはできません");

}
```

このコードでは、`10 / 0`の計算を試みていますが、0で割ることはできないためエラーが発生します。`catch`ブロックによってこのエラーが捕捉され、"0で割ることはできません"が出力されます。

## 関数

### 役割

- 関数は、特定のタスクを実行するためのコードの集まりです。
- これにより、コードの再利用性が向上し、プログラム全体の構造が整理され、メンテナンスが容易になります。
- 例として、ユーザー入力を受け取り、それに基づいて異なる処理を行う関数が挙げられます。

### コード例

```javascript{.numberLines caption="example05.js"}
function greet(name) {

  console.log("こんにちは、" + name + "さん！");

}

greet("太郎");
```

このコードでは、`greet`関数が定義されており、`name`という引数を取ります。この関数は、与えられた名前を使用して挨拶のメッセージを出力します。`greet("太郎")`の呼び出しにより、"こんにちは、太郎さん！"が出力されます。

## 無名関数

### 役割

- 無名関数（匿名関数）は、名前を持たない関数で、一時的な処理やイベントハンドラーとして使用されることが多いです。
- これにより、コードの簡潔化が図られ、一度限りの使用や即時実行が可能になります。
- 例として、イベントリスナー内で直接処理を記述することが挙げられます。

### コード例

```javascript{.numberLines caption="example07.js"}
document.getElementById("infoButton").addEventListener("click", function() {

  alert("情報を表示します！");

});
```

このコードでは、IDが`infoButton`のボタンにクリックイベントリスナーを追加し、無名関数を使用しています。ボタンがクリックされると、アラートで"情報を表示します！"というメッセージが表示されます。この例では、イベントリスナーに直接無名関数を記述することで、コードの簡潔さを保ちつつ、必要な機能を実装しています。

## イベントリスナー

### 役割

- イベントリスナーは、ユーザーのアクション（クリック、キーボード入力など）に応じて特定のコードを実行するために使用されます。
- これにより、インタラクティブなウェブページやアプリケーションを作成することが可能になります。
- 例として、ボタンがクリックされたときに情報を表示することが挙げられます。

### コード例

```javascript{.numberLines caption="example06.js"}
document.getElementById("myButton").addEventListener("click", function() {

  console.log("ボタンがクリックされました！");

});
```

このコードでは、IDが`myButton`のボタンにクリックイベントリスナーを追加しています。ボタンがクリックされると、コンソールに`"ボタンがクリックされました！"`と表示されます。
