# BUYMAスクレイピングアプリ

## 開発環境
- Python: 3.8.2
- pip: requirements.txt

## セットアップ

1. Google Chromeインストール
2. Chromeバージョン確認
- Chrome右上のGoogle Chromeの設定⇒[設定]⇒画面左下の[Chromeについて]
3.  Chromeドライバダウンロード
- 前項で確認したChromeと同じバージョンのドライバを以下よりダウンロード<br>
https://chromedriver.chromium.org/
4.  Chromeドライバ保存
- ダウンロードしたChromeドライバをアプリ(exe)と同じディレクトリに保存

## 使用方法

distディレクトリ内の`views.exe`ファイルを事前にダウンロードし、同じディレクトリにChromeドライバを保存しておくこと。

#### 商品検索

1. exeを起動（ダブルクリック）すると、下図の画面が表示される。
2. 商品検索タブをクリックし、商品検索モードにする。
3. 検索キーワード、チェックリスト、価格範囲を必要に応じて入力し、検索ボタンをクリック。
4. 検索ボタンをクリックすると、Chromeドライバの設定が実行され、画面上部にステータスが表示される。
- ドライバ設定が正常に実行されなかった場合は、ChromeとChromeドライバのバージョンが一致していることを確認してください。
5. ドライバ設定が正常に実行されたら、自動的にChromeが起動し、3項で指定した検索が実行される。
6. 検索内容をさらに詳細に絞りたい場合などは、Chromeの画面で再設定できる。
7. 設定完了後、抽出件数を入力し、抽出ボタンをクリック。
8. 抽出が完了したら、抽出データボタンをクリックして、抽出した情報の概要をプレビューできる。
9. プレビューしたデータで問題なければ、CSV保存ボタンをクリックしCSV保存する。CSVはアプリを同じディレクトリに保存される。

※アプリを実行すると、`logger.log`も同時に生成される。もし異常があった場合は、このログ情報をもとに調査を行います。

#### ショップ検索

表示のみ（動作しない、ダミー表示）

<img src=./buyma_app_view.png>

## 制作者
- Yoke