# my-fast-code

GitHub Issues を掲示板として閲覧できる Web アプリです。warai-lab/my-first-code リポジトリの Issue を読み込み、モバイルでも見やすいカード形式で表示します。

## 使い方

1. 掲示板を見る  
   https://warai-lab.github.io/my-fast-code/ を開くと、最新の投稿（Issue）が自動で読み込まれます。
2. 投稿する  
   ページ上部の「投稿する（GitHub Issues）」ボタンから Issue 作成画面に移動し、タイトルと本文を入力して送信します。GitHub アカウントでのログインが必要です。
3. 詳細を確認する  
   各カードをクリックすると、該当 Issue が GitHub 上で開き、コメントのやり取りや添付ファイルを確認できます。
4. Google Sites に埋め込む  
   上記 URL を iframe で指定すると、そのまま掲示板をサイト内に表示できます。Sites の「埋め込み」で URL を入力するだけで反映されます。

## 補足

- 表示されるのは Issue のみで、Pull Request は除外されます。
- GitHub API のレート制限により読み込みに失敗した場合は、時間を置いて再度アクセスしてください。
