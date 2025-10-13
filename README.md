# Awesome node

node.js お気に入りツール集

## 基本

- [xo](https://www.npmjs.com/package/xo) - Linter / Formatter / ESLintの最適解
- [ava](https://www.npmjs.com/package/ava) - 軽量なテストツール（標準テストが成熟するまでの代替）

## CLI制作

- [@clack/prompts](https://www.npmjs.com/package/@clack/prompts/v/0.0.2) - 対話形式のプロンプト
- [picocolors](https://www.npmjs.com/package/picocolors) - 出力のカラーリング
- [zx](https://www.npmjs.com/package/zx) - Bashコマンドの実行（癖あり）

## その他ツール

### .gitignore 生成

[toptal.com](https://www.toptal.com/developers/gitignore) サイト上から生成可能

#### curlでの生成

APIを用意してくれているのでcurl等からダウンロード可能です。

```bash
curl -L -o .gitignore https://www.toptal.com/developers/gitignore/api/node
```
