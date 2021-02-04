# 使い方

## インストール

```bash:
# インストール
$ npm install electron@9.1.1 --save-dev
```

## 起動

```bash:
# 起動
$ ./node_modules/.bin/electron .
```

## パッケージ化

```bash:
# パッケージマネージャインストール
$ npm install electron-packager@15.0.0 --save-dev
# パッケージ化実行
$ ./node_modules/.bin/electron-packager . CodeGene --platform=darwin,win32 --arch=x64 --electronVersion=9.1.1 --icon=assets/images/icon.icns
```
