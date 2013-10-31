## Installing

- Install [Composer](http://getcomposer.org) and place the executable somewhere in your `$PATH` (for the rest of this README,
I'll reference it as just `composer`)

- Add `darkyoung/upyun` to your project's `composer.json:

```json
{
    "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/darkyoung/upyun"
        }
    ],
    "require": {
        "darkyoung/upyun": "dev-master"
    }
}
```

- Install/update your dependencies
