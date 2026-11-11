# 作ったツール一覧（portfolio-site）

AIエンジニア講座で作った Python ツールを、カードで一覧にした Web ページです。
カードを押すと、それぞれの GitHub リポジトリ（コードと説明）が開きます。

公開 URL：https://portfolio-site-zhrq.vercel.app

## 使う技術

- HTML・CSS（1ファイルだけ。ビルドや JavaScript は使わない）
- Vercel（GitHub に push すると自動で公開・更新される）

## 事前準備

- GitHub アカウント
- Vercel アカウント（「Continue with GitHub」で作る。個人利用は無料の Hobby プラン）

## 使い方

- 手元で見る：`index.html` をブラウザで開く
- 公開：Vercel で このリポジトリを Import → Deploy
- 更新：`index.html` を直して `git push` すると、数十秒で公開中のページも変わる

## 秘密ファイルの用意の仕方

このページは鍵（API キーなど）を使わないので、秘密ファイルはありません。
鍵が要るときは、手元では `.env.local`（`.gitignore` 済み）に、公開先では Vercel の
「Settings → Environment Variables」に、同じ値を入れます。
