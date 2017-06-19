# 概要
このリポジトリは、動画ファイルと3DモデルをindexedDBで保存して利用するコードのサンプルです。

# 説明
indexed-db-movie/index.html内では、動画ファイルをネットからダウンロードしてindexedDBに保存して再生します。二回目以降の読み込みで、indexedDBにデータがある場合はindexedDBから動画データをロードして再生します。<br>
indexed-db-movie/deleteIndexedDB.htmlでは、上で作成したデータベースを削除します。<br>

indexed-db-model/index.htmlでは、Unityちゃんの3DモデルのglTF形式を読み込んでindexedDBに保存し、表示します。二回目以降の読み込みで、indexedDBにデータがある場合はindexedDBからモデルデータをロードして表示します。<br>
indexed-db-model/deleteIndexedDB.htmlでは、上で作成したデータベースを削除します。<br>
今回使用したモデルについて<br>
3Dmodel by [Horniman Museum - Dodo Model](https://sketchfab.com/models/ad10226b4f7a451ea23920a556c72a90)<br>
3Dmodel by [noxfcna - Mow Cop Castle, Stoke-on-Trent](https://sketchfab.com/models/07d6b7d0ee2943f4be9983e6f23db5ab#)<br>

# 試し方
このリポジトリをクローンした後、コマンドプロンプトからこのリポジトリに移動して、以下のコマンドを入力してnpmをインストールしてください

```
npm install
```

その後、ローカルサーバー上でこのリポジトリ内のページを試したい場合は以下のコマンドを実行してください。

```
npm run-script dev
```