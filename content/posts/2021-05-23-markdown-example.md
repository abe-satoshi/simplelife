---
title: Markdownの書き方：備忘録
type: post
date: 2021-05-23T09:00:47+00:00
lastmod: 2022-05-01T09:00:47+00:00
url: /posts/markdown-example/
image: /images/markdown-mark.png
categories:
- Markdown
---
ブログでも仕事でも、Markdownが使えると便利。自分の備忘録を兼ねて。

<svg xmlns="http://www.w3.org/2000/svg" width="208" height="128" viewBox="0 0 208 128"><rect width="198" height="118" x="5" y="5" ry="10" stroke="#000" stroke-width="10" fill="none"/><path d="M30 98V30h20l20 25 20-25h20v68H90V59L70 84 50 59v39zm125 0l-30-33h20V30h20v35h20z"/></svg><br>
出典：[Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Markdown-mark.svg)

## 見出し

<pre>
<code>
「#」の後に空白でタイトル、「#」の数で異なる

# タイトル h1
## タイトル h2
### タイトル h3
#### タイトル h4
</code>
</pre>

SEOの観点から、ブログのタイトルはh1、記事は、h2、Markdownでは「##」から使うのが一般的。

## リスト・箇条書き

Markdown、HTMLで書いた場合の比較

<pre>
<code>
箇条書きは「-」の後に空白

- リスト
- リスト

数字付きの箇条書きは「数字」の後に空白

1. リスト
2. リスト

1を続けても自動でカウントしてくれる

1. リスト
1. リスト
</code>
</pre>

1つ目が黒丸、2つ目が白丸

- リスト
    - リスト
    - リスト
- リスト
- リスト
    - リスト
    - リスト

1つ目が黒丸、2つ目が数字

- リスト
- リスト
    1. リスト
    2. リスト

1つ目が数字、2つ目も数字

1. リスト
1. リスト
    1. リスト
    1. リスト

1つ目が数字、2つ目が白丸

1. リスト
1. リスト
    - リスト
    - リスト

## 強調

<pre>
<code>
文章で強調するときは、**強調する部分**を「**」で挟む。
</code>
</pre>

文章で強調するときは、**強調する部分**を「**」で挟む。

## 改行

<pre>
<code>
改行は、Markdownでは表現できないので、&lt;br>を使う。
</code>
</pre>

改行は、Markdownでは表現できないので、<br>を使う。← 改行された状態

## 引用

<pre>
<code>
引用は、行頭に「>」を使う。

>これは偉人の引用

複数行にするときは、「>」だけの行を入れる。

>これも同じように偉人の引用
>
>これも同じように偉人の引用
</code>
</pre>

引用は、行頭に「>」を使う。

>これは偉人の引用

複数行にするときは、「>」だけの行を入れる。

>これも同じように偉人の引用
>
>これも同じように偉人の引用

## リンク

<pre>
<code>
以下のように、[]と()で囲う。

[リンクのテキスト](https://)
</code>
</pre>

[リンクのテキスト](#)

## 画像

<pre>
<code>
画像は、

{{&lt; figure src="/images/画像ファイルの名称(拡張子は.jpgまたは.png)" class="center" width="横幅のサイズ" height="縦幅のサイズ">}}

例
{{&lt; figure src="/images/markdown-mark.png" class="center" width="200" height="123">}}
</code>
</pre>

{{< figure src="/images/markdown-mark.png" class="center" width="200" height="123">}}