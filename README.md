# 福岡イベントカレンダー

画像に近い月別一覧表デザイン。前月・翌月、検索、ジャンル・地域絞り込み、印刷、スマートフォン表示に対応。

## GitHub Pagesで無料公開
1. GitHubで `fukuoka-event-calendar` というPublic repositoryを作成
2. ZIP内のファイルをリポジトリ直下へアップロードしてmainへ保存
3. Settings → Pages → Build and deployment → Source を GitHub Actions に設定
4. Actionsタブで「Deploy website」を実行
5. 公開URL: https://あなたのGitHubユーザー名.github.io/fukuoka-event-calendar/

## 自動更新
Actions →「Update events」→ Run workflowで初回実行。以後6時間ごとに実行。

## 収集範囲と注意
現在は福岡市公式RSSの2フィードが対象。RSS記事のリンク先に開催日付きschema.org Eventデータがある場合のみ掲載します。福岡県内の全イベントを網羅するものではありません。北九州市・久留米市など県内自治体、主要会場、主催者、観光協会等の公式RSS/APIを追加して拡張してください。取得元の利用規約・robots.txt・著作権・アクセス頻度を確認して運用してください。
