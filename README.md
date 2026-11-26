# DualSub 紹介ページ

GitHub Pages 向けの静的ランディングページです。ビルド工程・外部スクリプト・外部フォント・解析タグはありません。

## 構成
- `index.html`：日本語の紹介ページ
- `en/index.html`：英語の紹介ページ（日本語版と相互に hreflang でリンク）
- `assets/dualsub-landing/styles.css`：専用スタイル
- `assets/dualsub-landing/og-image.png`・`og-image-en.png`：SNS共有用のリンクカード画像（1200×630、既存デモ素材から作成）
- `assets/dualsub-landing/favicon-32.png`・`apple-touch-icon.png`：アイコンから縮小・拡大したファビコン
- `assets/dualsub-landing/*.png`（上記以外）：DualSubオリジナルのアイコンとストア掲載用デモ素材（配信作品の映像・実再生キャプチャではありません）

## 公開前に確認
- canonical・hreflang・og:url・og:image は `https://studio344.github.io/dualsub-site/` を前提にしています。独自ドメインなど別のURLで配信している場合は書き換えてください。
- デスクトップ・タブレット・スマートフォン幅での実ブラウザー表示を確認してください。現在は構造チェックのみ完了しており、実画面検証は未完了です。
- Chrome・Edge・Pro・プライバシーポリシーへのリンクと最新の料金・対応条件を再確認してください。
- GitHub Pages の設定・公開は、このファイルの存在だけでは完了しません。公開後は配信URLとファイル内容を確認してください。

© Studio344. 作品の映像・実字幕・第三者の画像は含みません。背景と字幕例はオリジナルの表示イメージです。デモ画像は既存素材のピクセルを維持し、字幕デモは中央の表示部分のみCSSで切り出しています。
