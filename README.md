# GASでTypescript
## 参考URL [Google Apps ScriptsでTypescriptが超簡単に使えるようになった](https://tech.actindi.net/2018/09/10/083314)

## 環境構築

### npmパッケージインストール

```
$ mkdir clasp-ts-sample
$ cd clasp-ts-sample
$ npm init -y
$ npm install @google/clasp tslint -D
$ npm install @types/google-apps-script -S
$ npx tslint --init # tslint は必須ではありませんが、大人のたしなみとして導入しましょう。
```

npxに関しては[こちら](https://qiita.com/tonkotsuboy_com/items/8227f5993769c3df533d)参照