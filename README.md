# capybala.github.io

GitHub pages for [capybala.com](https://capybala.com/)

## 開発に必要な最初の作業（一度だけ必要）

- Ruby 2.4 以降

```
cd ~/capybala.github.io
bundle install
```

## 開発用サーバーの起動

```
cd ~/capybala.github.io
bundle exec jekyll serve --watch
```

この状態で、ブラウザで [http://localhost:4000/](http://localhost:4000/) にアクセスすると表示される。

サーバーの終了は Ctrl+C

## ファイル・ディレクトリについて

- `_config.yml`: サイトに関する設定
- `_layouts/`: 各ページのテンプレートとなる HTML
- `_posts/`: 各記事の Markdown
- `_site/`: Jekyll によって生成される HTML など。**このフォルダのファイルは編集しないこと**
- `CNAME`: カスタムドメインの設定
- `css/`: CSS/SCSS ファイル
- `images/`: 画像ファイル
- `index.html`: トップページ
- `js/`: JavaScript ファイル
- `README.md`: この説明ファイル

## 公開

GitHub にプッシュ（Sync）すると公開される。
