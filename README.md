# PHP CI Box

## How to use

```ruby
# Vagrantflie
Vagrant::Config.run do |config|
    config.vm.box = "php-ci"
    config.vm.box_url = "http://static.jubianchi.fr/boxes/php-ci.box"
end
```

## What is installed

<table>
<thead><tr><th>Utility</th><th>Version</th></thead><tbody>
<tr><th>PHP (system default)</th><td>PHP 5.3.10-1ubuntu3.4 with Suhosin-Patch (cli) (built: Sep 12 2012 19:00:43)<br />
Copyright (c) 1997-2012 The PHP Group<br />
Zend Engine v2.3.0, Copyright (c) 1998-2012 Zend Technologies<br />
    with Xdebug v2.2.1, Copyright (c) 2002-2012, by Derick Rethans</td></tr>
<tr><th>atoum</th><td>atoum version nightly-1635-201212121023 by Frédéric Hardy (phar:///usr/share/atoum/mageekguy.atoum.phar)</td></tr>
<tr><th>PHPMD</th><td>PHPMD 1.4.1 by Manuel Pichler</td></tr>
<tr><th>PHP_Depend</th><td>PHP_Depend 1.1.1snapshot201209122131 by Manuel Pichler</td></tr>
<tr><th>PHP_CodeSniffer</th><td>PHP_CodeSniffer version 1.4.3 (stable) by Squiz Pty Ltd. (http://www.squiz.com.au)</td></tr>
<tr><th>PhpSwitch</th><td>PhpSwitch version 0.1</td></tr>
<tr><th>Phing</th><td>Phing 2.5.0snapshot20121214093509</td></tr>
<tr><th>PHPUnit</th><td>PHPUnit 3.7.10 by Sebastian Bergmann.</td></tr>
</tbody></table>


## PHP versions

```shell
# Switch PHP version
$ source /usr/share/phpswitch/.phpswitch/.phpswitchrc
$ php switch php-<version>

# Restore default PHP version
$ php switch off
```

<table>
    <thead>
        <tr>
            <th>Version</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th>php-5.3.18</th>
            <td>
                PHP 5.3.18 (cli) (built: Nov 22 2012 21:48:43)<br/>
                Copyright (c) 1997-2012 The PHP Group<br/>
                Zend Engine v2.3.0, Copyright (c) 1998-2012 Zend Technologies<br/>
            </td>
        </tr>
        <tr>
            <th>php-5.4.8</th>
            <td>
                PHP 5.4.8 (cli) (built: Nov 22 2012 21:44:21)<br/>
                Copyright (c) 1997-2012 The PHP Group<br/>
                Zend Engine v2.4.0, Copyright (c) 1998-2012 Zend Technologies<br/>
            </td>
        </tr>
    </tbody>
<table>

## You'll also find...

* Sonar v3.3 ([http://localhost:9001/](http://localhost:9001)) with PHP plugin ([jubianchi/sonar-php](https://github.com/jubianchi/sonar-php))
* Jenkins v1.491 ([http://localhost:8181/](http://localhost:8181))