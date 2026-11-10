# ZERO PROTOCOL — すべてをゼロへ

宇宙に残された「残量」を削り、削減で得た断片を設備・研究へ再投資して、すべてをゼロへ導くデクリメンタル・インクリメンタルゲームです。

## Features
- TypeScript + Vite。バックエンド不要の完全静的アプリ
- 5つの領域を自動で減衰させる設備と、連鎖する生産ライン
- 研究ツリー、領域ごとの強化、ランダムな宇宙イベント、実績
- 全領域をゼロにして次の宇宙へ進む「再起動」と恒久アップグレード
- localStorageセーブ、オフライン進行、手動セーブ/リセット
- PC・スマートフォン対応

## Development
```bash
npm install
npm run dev
npm run build
npm run preview
```

## GitHub Pages
`main` ブランチへの push で `.github/workflows/deploy.yml` がビルドし、GitHub Pagesへデプロイします。リポジトリの Settings → Pages → Build and deployment で Source を **GitHub Actions** に設定してください。

このゲームは相対アセットパスでビルドするため、ユーザー名やリポジトリ名に依存しません。
