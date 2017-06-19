#概要
indexed DBで動画データを保存して扱うテスト

#モバイルでのテストとその結果
OS		: iOS 8.0/9.0/10.0
ブラウザ : safari
全てにおいて動作。ただし、ios8.0ではindexedDB周りに致命的なバグが存在するため、非推奨。

OS : Android 4.4
ブラウザ : Android標準ブラウザ
機能しない。そもそもblob形式で動画を再生することができなかったので、indexedDBに動画データを保存できても無意味。

OS : Android 4.4
ブラウザ : Google Chrome 58.0
正常動作。Android4.4で機能するので、Chromeで閲覧する場合はほぼ問題なく動くといって良い。

#参照サイト
IndexedDBの使い方
http://qiita.com/butakoma/items/2c1c956b63fcf956a137

BlobURL〜端末のファイルにアクセス出来る魔法のURL
http://www.pondad.com/?p=9443

iOS8 で IndexedDB を使うための 5 つの注意点 - WebOS Goodies
http://webos-goodies.jp/archives/5_pitfalls_of_indexeddb_on_ios8.html