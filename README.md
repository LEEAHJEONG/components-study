# 기본 설치 및 파일 생성

- `npm i @emotion/react`
- `npm i @emotion/styled`

- .prettierrc.json 파일 생성

```json
{
  "singleQuote": false,
  "semi": true,
  "useTabs": false,
  "tabWidth": 2,
  "trailingComma": "all",
  "printWidth": 80,
  "arrowParens": "avoid",
  "endOfLine": "auto"
}
```

- `npm install eslint-config-react-app --save-dev`
- `npx eslint --init`
- `npm i eslint --dev`
- `npm install eslint-config-prettier --save-dev`
- .eslintrc.js 파일 수정

```js
extends: [
    "eslint:recommended",
    "plugin:react/recommended",
    "prettier"
],
rules: {
  "react/react-in-jsx-scope": "off",
  "react/prop-types": "off",
  "no-unused-vars": "off",
},
```

- `npm install @babel/plugin-proposal-private-property-in-object --dev`

- `npm i axios`
