# 環境設定
①ツールインストール
```
$ npm install
```

②electron立ち上げ
package.jsonを以下に書き換え
```
    "electron": "concurrently \"npm:start\" \"wait-on http://localhost:3000 && electron ./public\""
```

```
$ npm run electron
```

③


