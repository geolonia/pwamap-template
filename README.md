# PWA MAP Template

Geolonia PWA Map テンプレート は、GitHub と CSV を使って、素早く PWA の地図アプリが作れるテンプレートです。

【デモURL】  
https://geolonia.github.io/pwamap-template/

## ご利用方法

* [[Fork]](https://github.com/geolonia/pwamap-template/fork) ボタンをクリックして、このテンプレートを自分のリポジトリにフォークしてください。
* `data.csv` を以下の通りに編集してコミットすると数分後に、`https://<あなたのGitHubユーザー名>.github.io/<リポジトリ名>/` 形式の URL で地図アプリが立ち上がります。（[サンプル URL](https://geolonia.github.io/pwamap-template/)）
* ファイル名は変更しないでください。

## 1. GitHub Pages の設定

* [Actions] タブ > [I understand my workflows, go ahead and enable them] を選択します。
<img width="600" alt="スクリーンショット 2025-09-05 9 37 59" src="https://github.com/user-attachments/assets/4f92bd27-3858-4fc0-8a0b-46a7b687b567" />

* [Settings] タブ > [Pages] > [GitHub Actions] を選択します。
<img width="600" alt="スクリーンショット 2025-09-04 15 35 10" src="https://github.com/user-attachments/assets/6fb61958-8038-422f-9a75-9a212f9abc54" />

## 2. データの編集 (`data.csv`)

マップに表示するスポット情報は `data.csv` ファイルで管理します。このファイルは以下のヘッダーを持つCSV形式である必要があります。編集して GitHub にアップロードすると地図アプリが作成されます。

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
