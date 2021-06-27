# 手書きメモ（テキスト変換）

## 使い方
まず、次のツールがインストールされていることを確認してください。
- [npm](https://www.npmjs.com/get-npm)
- [Node.js](https://nodejs.org/en/)

次に、既存のプロジェクトを使用するか、以下のコマンドを使用して新しいプロジェクトを開始します。
```
npm init
```

依存関係をインストールするには、開発フォルダーに次のように入力します。
```
npm install iink-js
```

[index.html](https://raw.githubusercontent.com/MyScript/iinkJS/master/examples/dev/index.html)のコンテンツを 開発中のフォルダーに再コピーします。index.htmlファイルを編集し、属性applicationkeyとhmackey属性を電子メールで受け取った値に置き換えます。

次に、依存関係とindex.htmlファイルを含むディレクトリを提供するWebサーバーを起動します。
```
python -m http.server
```

最後に、開く ブラウザで[http://localhost:8000](http://localhost:80001)



ref: https://developer.myscript.com/getting-started/web