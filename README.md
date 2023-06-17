```sh
yarn create vite hello-world --template=react-ts
yarn add prettier --dev
yarn add eslint-config-prettier --dev

# Prettier と ESlint で設定が衝突してないかチェック
yarn eslint-config-prettier 'src/**/*.{js,jsx,ts,tsx}'
```
