# FUMA 小説サイト starter

GitHub Pages にそのまま置ける、作品本文用のスターターです。

## ファイル

- `story-template.html` → 新しい作品を作るときの元ファイル
- `story-example.html` → サンプル作品
- `style.css` → 作品本文の共通デザイン

## 新しい作品を追加する方法

1. `story-template.html` を複製する
2. ファイル名を変える
   - 例：`summer.html`
   - 例：`cat.html`
3. HTMLの次の4か所だけ変更する
   - `<title>`
   - `<h1>`
   - 日付・ジャンル・読了時間
   - `<article>` の本文
4. `contents.html` に作品を1行追加する
5. GitHub Pages に push

本文は段落ごとに、

`<p>ここに文章</p>`

と書けばOKです。

CSSは触らなくて大丈夫です。
