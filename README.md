# vite reaxt ts + lint

- ESLint
- StyleLint
- Prettier


- eslint-plugin-react
- eslint-plugin-react-hooks
- @typescript-eslint/eslint-plugin
- eslint-plugin-import
- eslint-plugin-jsx-a11y
- @typescript-eslint/parser”


prettier 導入

npm install prettier eslint-config-prettier --save-dev

衝突するルールがないか確認
npx eslint-config-prettier 'src/**/*.{js,jsx,ts,tsx}'

    "int": "eslint 'src/**/*.{js,jsx,ts,tsx}'",
    "lint:fix": "eslint --fix 'src/**/*.{js,jsx,ts,tsx}'",
    "lint:conflict": "eslint --print-config .eslintrc.js | eslint-config-prettier-check",
    "preinstall": "typesync”

