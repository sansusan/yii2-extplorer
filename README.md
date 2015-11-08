yii2-phpfreechat
================

Extension that is a wrapper of the PHP free chat.

## Demo

[http://yiimarket.ho96.com/phpfreechat](http://yiimarket.ho96.com/phpfreechat "http://yiimarket.ho96.com/phpfreechat")

## Installation

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
$ php composer.phar require ho96/yii2-phpfreechat "dev-master"
```

or add

```
"ho96/yii2-phpfreechat": "dev-master"
```

to the ```require``` section of your `composer.json` file.

## Usage

```php
use ho96\phpfreechat\PHPFreeChat;
echo PHPFreeChat::widget();
```

## License

**yii2-phpfreechat** is released under the BSD 3-Clause License. See the bundled `LICENSE.md` for details.