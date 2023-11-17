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
