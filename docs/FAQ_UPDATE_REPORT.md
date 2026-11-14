# FAQリンク追加 修正報告

独立したFAQページはありません。既存の first/index.html 内のFAQ（質問・回答5件）を利用し、新規ページは作成していません。

## 変更
16ページのメインナビ（PC・スマホ共通）とフッターに「よくある質問（FAQ）」を追加。リンク先は /first/#faq。
first/index.html のFAQ sectionに id="faq" を追加。
CSS、JavaScript、画像、質問・回答、デモフォーム本文・処理は変更なし。

## 確認済み
全16ページのリンクがナビ・フッター各1件（計32件）。リンク先HTMLと一意のFAQアンカーが存在し、5件の質問・回答を含むことをソースで確認。
変更前との差分がリンク追加とアンカーのみであることを自動照合。CSS・JSは変更前とバイト一致。

## 未確認
プレビュー起動が relay could not open browser port 4173: timed out waiting for relay readiness で失敗。
360px・390px・768px・1440pxの実表示、ブラウザーでのリンク遷移・FAQ開閉、メニューの折返し・はみ出しは未確認です。コード上の検査を実操作の合格として扱っていません。

## 配置
GitHub・Netlifyへの公開・保存は行っていません。本人限定Sitesプレビュー用に配置。他サイトは変更していません。

## 変更ファイル
- dist/index.html
- dist/404.html
- dist/aesthetic/index.html
- dist/first/index.html
- dist/access/index.html
- dist/contact/index.html
- dist/dermatology/index.html
- dist/about/index.html
- dist/news/index.html
- dist/privacy/index.html
- dist/treatments/ipl/index.html
- dist/treatments/peeling/index.html
- dist/treatments/ion/index.html
- dist/news/visit/index.html
- dist/news/philosophy/index.html
- dist/news/open/index.html

納品用ファイル：docs/FAQ_UPDATE_REPORT.md、dist/delivery/FAQ_UPDATE_REPORT.md、dist/delivery/index.html、dist/delivery/naginoha-clinic.zip。
