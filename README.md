tomk79/px2-fess
=========

FESS document modues for Pickles 2.


## Usage - 使い方

### 1. Pickles2 をセットアップ

### 2. composer.json に追記

```
{
    "require": {
        "tomk79/px2-fess": "dev-master"
    }
}
```

### 3. composer を更新

```
$ composer update
```

### 4. px-files/config.php に追加

```
// config for Pickles2 Desktop Tool.
@$conf->plugins->px2dt->paths_module_template["FESS"] = "./vendor/tomk79/px2-fess/modules/";
```


## License

MIT License


## Author

- (C)Tomoya Koyanagi <tomk79@gmail.com>
- website: <http://www.pxt.jp/>
- Twitter: @tomk79 <http://twitter.com/tomk79/>


