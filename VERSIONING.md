# Portfolio Versioning

このフォルダでは、公開候補のポートフォリオを版ごとに保存しています。

## Current

- `index-improved.html`
- Version: `v2.8.0`
- Summary: Servicesの8項目からも見積もりアンケートを開ける導線を追加

## Saved Versions

### `versions/2026-06-08_153109_before_page_visuals`

- Version: `v2.0.0`相当
- 今回の「各ページに画像を追加する前」の状態です。
- 元に戻したい場合は、このフォルダ内の`index-improved.html`と画像一式を使用します。

### `versions/2026-06-08_153109_v2.1.0_page_visuals`

- Version: `v2.1.0`
- About / Works / Contactに画像入りのビジュアル帯を追加した状態です。
- フッター表記も`v2.1.0`に更新しています。

### `versions/2026-06-08_before_home_visual_upgrade`

- Version: `v2.1.0`
- Home内の各セクションを画像主体のデザインへ変更する直前の状態です。

### `versions/2026-06-08_v2.2.0_home_visual_upgrade`

- Version: `v2.2.0`
- Services / Price Guide / Work Flow / Why Choose Meの各カードへ実作品画像を追加
- HomeのAboutを背景画像と人物写真を組み合わせた構成へ変更
- 各セクションに作品画像を使った背景デザインを追加

### `versions/2026-06-08_v2.3.0_unique_visuals`

- Version: `v2.3.0`
- セクション背景での作品画像使い回しを撤去
- Servicesは8種類の異なる作品画像を使用
- Price Guideは画像なしの色分け料金カードへ変更
- Work FlowとWhy Choose MeはServicesとは異なる素材を使用
- Aboutはトップ背景を再利用せず、専用のグリッド背景と人物写真で構成
- Image 2.0は3回試行したものの、生成サービス側のServerErrorで新規画像を取得できず

### `versions/2026-06-09_v2.4.0_service_images`

- Version: `v2.4.0`
- Servicesの8項目すべてを、専用に作成した異なるSVGビジュアルへ変更
- YouTube、SNS、ロゴ、チラシ、名刺、商品ラベル、電子書籍、GPTsの用途が一目で分かる構成
- 各画像で配色、モチーフ、レイアウトが重ならないように調整

### `versions/2026-06-09_v2.5.0_workflow_images`

- Version: `v2.5.0`
- Work Flowの「ご相談・初稿制作・修正対応・納品」に専用画像を作成
- 相談風景、デザイン制作画面、修正比較、複数形式での納品をそれぞれ描き分け
- 4枚は統一感のある立体的なクリエイティブ表現で構成

### `versions/2026-06-09_v2.6.0_why_choose_images`

- Version: `v2.6.0`
- Why Choose Me?の5項目すべてに専用画像を作成
- AIによる高速制作、媒体別提案、編集可能な共有データ、丁寧なヒアリング、こまめな連絡を描き分け
- 統一感のある立体的な表現を保ちながら、場面と配色が重ならないように調整

### `versions/2026-06-09_v2.7.0_estimate_questionnaire`

- Version: `v2.7.0`
- Price Guideの矢印と相談ボタンから、サービス別の見積もりアンケートを表示
- YouTube、SNS、ロゴ、チラシ、名刺、GPTsごとに質問内容を最適化
- 回答後はContactへ移動し、件名とメッセージ欄へ回答内容を自動入力
- 入力内容を確認・追記して、従来どおりメールソフトから送信可能

### `versions/2026-06-09_v2.8.0_services_estimate_links`

- Version: `v2.8.0`
- Servicesの画像と「質問に答えて相談」ボタンから見積もりアンケートへ接続
- Price Guideと同じアンケート・Contact自動入力の流れを共通利用
- 商品ラベルと電子書籍表紙にも、それぞれ専用の質問項目を追加
- Servicesの8項目すべてから見積もり相談を開始可能

## Rollback Guide

元に戻したい場合は、戻したい版のフォルダに入っている`index-improved.html`を現在の`outputs/index-improved.html`として使います。

画像も同じフォルダに保存しているため、HTMLと画像を同じ場所に置くと表示が崩れにくくなります。
