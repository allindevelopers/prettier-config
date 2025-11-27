# `@allindevelopers/prettier-config`

[@allindevelopers](https://github.com/allindevelopers) prettier config

## Usage

**Install**:

```shell
npm install --dev @allindevelopers/prettier-config
```

- **Add to `package.json`**:

```jsonc
{
	// ...
	"prettier": "@allindevelopers/prettier-config"
}
```

- **Add to `.prettierrc.json`**:

```json
"@allindevelopers/prettier-config"
```

- **Add to `.prettierrc.js`**:

```js
module.exports = {
	...require("@allindevelopers/prettier-config"),
	// ...
};
```

## Release new version

```shell
npx np
```
