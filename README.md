# style-config-sensetime

> Sensetime DCP shared config for stylelint.

## Installation

Install the correct versions of each package, which are listed by the command:

```console
npm info "style-config-sensetime@latest" peerDependencies
```

If using npm 5+, use this shortcut

```console

npx install-peerdeps --dev style-config-sensetime
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
