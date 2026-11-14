# 凪の葉 皮ふ科・美容皮ふ科
Lumi Designのポートフォリオ用、架空クリニックの静的サイト。実際の医療・予約・送信は提供しません。

## ブランド
「肌と、心に、穏やかな日々を。」深い青緑・生成り・セージ、明朝とゴシック、自然光とオークの空間。凪と葉のイメージをワードマークと曲線で表現。

## 構成
`dist/` は完成データ。HTML/CSS/JavaScriptのみでビルド不要。16ページ（404を含む）、3施術詳細、3お知らせ詳細。`netlify.toml` はNetlify公開・ヘッダー設定。`docs/` に公開手順、テスト報告、医療広告確認表。

`python3 -m http.server 8080 --directory dist` でローカル閲覧。`npm run check` でJavaScript構文検査。ルート絶対パスを使用するため file:// ではなくHTTPで閲覧してください。

## 編集
各ページのHTMLを直接編集します。共通CSSは `dist/style.css`、動作は `dist/app.js`。フォームは通信せず、DOMのtextContentで確認内容を出力します。バックエンド、分析タグ、Cookie保存はありません。

デモの誤認防止のため noindex, follow を設定。公開ドメイン変更時はOGP、sitemap、robotsを一括更新してください。

## 状態
静的検査済み。実ブラウザーでの寸法・操作確認は環境制約で未完了。公開・利用前に docs/TEST_REPORT.md と docs/MEDICAL_REVIEW.md を確認してください。
