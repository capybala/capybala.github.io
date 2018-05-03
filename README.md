capybala.github.io
==================

GitHub pages for [capybala.com](https://capybala.com/)


開発に必要な最初の作業（一度だけ必要）
-------------------------------------

[Jekyll](http://jekyllrb.com/) 2.0以降のインストール

```
sudo gem install jekyll
```


開発用サーバーの起動
--------------------

```
cd ~/capybala.github.io
jekyll serve --watch
```

この状態で、ブラウザで [http://localhost:4000/](http://localhost:4000/) にアクセスすると表示される。

サーバーの終了はCtrl+C


ファイル・ディレクトリについて
------------------------

* `_config.yml`: サイトに関する設定
* `_layouts/`: 各ページのテンプレートとなるHTML
* `_posts/`: 各記事のMarkdown
* `_site/`: Jekyllによって生成されるHTMLなど。**このフォルダのファイルは編集しないこと**
* `CNAME`: カスタムドメインの設定
* `css/`: CSS/SCSSファイル
* `downloads/`: ダウンロードするソフトウェアの置き場
* `images/`: 画像ファイル
* `index.html`: トップページ
* `js/`: JavaScriptファイル
* `README.md`: この説明ファイル

公開
----

GitHubにプッシュ（Sync）すると公開される。
