# style-config-sensetime

> Sensetime DCP shared config for stylelint.

## Installation

```console

npm install style-config-sensetime --save-dev
npm install-peerdeps --dev style-config-sensetime

```

## Usage

Set your stylelint config to:

```json
{
  "extends": "style-config-sensetime"
}
```

### Extending the config

Simply add a `"rules"` key to your config and add your overrides there.

For example, to change the `indentation` to tabs:

```json
{
  "extends": "style-config-sensetime",
  "rules": {
    "comment-no-empty": null
  }
}
```

## [License](LICENSE)
