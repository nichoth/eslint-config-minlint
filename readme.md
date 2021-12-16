# eslint config minlint

Minimal linting settings in a shareable eslint config.

* 4 spaces
* no semicolons
* max line length of 80 columns
* no unused variables, but unused parameters are ok
* single quotes, but double are ok for escaping purposes
* no-undef

## install

```
$ npm i -D eslint eslint-config-minlint
```

## use

```
$ npm run lint
```

package.json
```js
{
    "scripts": {
        "lint": "eslint ."
    }
}
```

.eslintrc
```js
{
    "extends": ["minlint"]
}
```

