# Linter Configs

Linters @ Williams New York

## SCSS

### Packages

* Linter:
  * [stylelint](https://github.com/stylelint/stylelint)
* Modules:
  * [postcss](https://github.com/postcss/postcss)
  * [stylelint-config-recommended-scss](https://github.com/stylelint-scss/stylelint-config-recommended-scss)
  * [stylelint-order](https://github.com/hudochenkov/stylelint-order)
  * [stylelint-stylistic](https://github.com/stylelint-stylistic/stylelint-stylistic)

#### Install

```
npm install -g stylelint postcss stylelint-config-recommended-scss stylelint-order @stylistic/stylelint-plugin
```

### Config

Repo: `stylelintrc`
System: `~/.stylelintrc`

#### Install

```
ln -s "$(readlink -f stylelintrc)" ~/.stylelintrc
```

## Javascript

### Packages

* Linter:
  * [eslint](https://github.com/eslint/eslint)
* Modules:
  * [@babel/eslint-parser](https://github.com/babel/babel-eslint)
  * [eslint-plugin-vue](https://github.com/vuejs/eslint-plugin-vue)
  * [eslint-plugin-json](https://github.com/azeemba/eslint-plugin-json)

#### Install

```
npm install -g eslint @babel/eslint-parser eslint-plugin-vue eslint-plugin-json
```

### Config

Repo: `eslintrc`
System: `~/.eslintrc`

#### Install

```
ln -s "$(readlink -f eslintrc)" ~/.eslintrc
```
