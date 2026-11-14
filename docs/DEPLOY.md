# GitHub・Netlify 公開手順
1. ZIPを展開し、README、テスト報告と医療広告確認表を確認。
2. GitHubに新しい空リポジトリを作成。既存のBIG WAN、Lumi Design、ウェディング、美容サロン、余景のリポジトリは選択しない。
3. このフォルダーのファイルをコミット・プッシュ（秘密情報なし）。Sites専用 `.openai` はNetlifyでは不要。
4. Netlifyの「Add new project」から新規GitHubリポジトリを接続。ビルドコマンドは空欄、公開フォルダーは `dist`。`netlify.toml` も同設定。
5. Netlify発行のHTTPS URLで表示。未知のパスで404ページが返ることを確認。
6. すべてのHTMLの `og:url` / `og:image`、sitemap.xml、robots.txtのドメインを新しいURLへ変更。OG画像のURLを確認。
7. 360・390・768・1440pxでテスト報告の未確認項目を実施。キーボード、フォーム、FAQも確認。
8. 本番に医療サービスとして転用する場合は架空設定の置き換えと医師・専門家レビューが必須。ポートフォリオとしては架空表示とnoindexを維持。

GitHubの保存先が指定されていないため、既存リポジトリへの書き込みは実施しません。納品ZIPをそのまま新規リポジトリに保存できます。Netlifyアカウントへの直接操作は実施していません。
