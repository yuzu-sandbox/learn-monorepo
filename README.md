# monorepoの練習用リポジトリ

yarn workspaceを利用したmonorepoのテスト用リポジトリ

`package_b`が`package_a`に依存している

## 確認手順

```sh
yarn install

cd packages/project_b
node src/index.js // => 3
```