# Deprecated

このパッケージは非推奨となりました
今後は [anoare](https://github.com/ichiql/anoare) をご使用ください :)

This package has been deprecated.
Use https://github.com/ichiql/anoare instead.

---

# @ichiql/stringify

```shell
pnpm add @ichiql/stringify
npm install @ichiql/stringify
yarn add @ichiql/stringify
```

なにかを文字列化する(bigint supported JSON.stringify)

String something (bigint supported JSON.stringify)

```js
import stringify from '@ichiql/stringify'

await stringify({ name: 'haruhi', num: BigInt(8) }) // { "name": "haruhi", "num": "8" }
```
