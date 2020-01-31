# conceal

Simply store secrets in MacOS Keychain Access for use by [Summon](https://cyberark.github.io/summon).

## Installation

```shell
wget 'https://raw.githubusercontent.com/infamousjoeg/conceal/master/conceal' -O /usr/local/bin
```

## Usage

### `conceal service/secrettype`

Will create a password in MacOS Keychain Access for use by Summon.

`service/secrettype` can be anything: `dockerhub/token` or `github/gpgkey` or `jenkinsci/admin`.

You will be securely prompted for the secret value.

### `conceal --help` or `conceal -h`

Will display help for conceal.

### `conceal --version` or `conceal -v`

Check conceal's current version.

## License

MIT

[![Buy me a coffee][buymeacoffee-shield]][buymeacoffee]

[buymeacoffee]: https://www.buymeacoffee.com/infamousjoeg
[buymeacoffee-shield]: https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png
