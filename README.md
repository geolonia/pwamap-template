# PWA MAP Template

Geolonia PWA Map テンプレート は、GitHub と CSV を使って、素早く PWA の地図アプリが作れるテンプレートです。


<img width="1235" height="799" alt="スクリーンショット 2025-09-04 15 25 01" src="https://github.com/user-attachments/assets/23b73de5-3ff7-4893-916f-b4a3dfe08f84" />


## ご利用方法

* [[Use this template]](https://github.com/geolonia/pwamap-template/generate) ボタンをクリックして、このテンプレートを自分のリポジトリにコピーしてください。
* GitHub Pages を設定してください。
* `data.csv` を以下の通りに編集してコミットすると数分後に、`https://<あなたのGitHubユーザー名>.github.io/<リポジトリ名>/` 形式の URL に編集したデータを表示する地図アプリが立ち上がります。（[サンプル URL](https://geolonia.github.io/pwamap-template/)）

## データ形式 (`data.csv`)

マップに表示するスポット情報は `data.csv` ファイルで管理します。このファイルは以下のヘッダーを持つCSV形式である必要があります。

*   `タイムスタンプ`
*   `カテゴリ`
*   `画像`
*   `緯度`
*   `経度`
*   `スポット名`
*   `紹介文`
*   `Instagram`
*   `Twitter`
*   `公式サイト`
*   `Facebook`

各列のデータは、マップ上のピンや情報ウィンドウに表示されます。
