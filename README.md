# wkhtmltopdf binaries all in one place

[http://wkhtmltopdf.org/downloads.html](http://wkhtmltopdf.org/downloads.html)

## Install

1. Install Composer:

    ```    
    curl -s https://getcomposer.org/installer | php
    ```
    
2. Add to your `composer.json` file:

    ```js
    {
        "require": {
            "profburial/wkhtmltopdf-binaries": "1.0"
        }
    }
    ```

3. All the binaries are symlinked to the following paths:

```vendor/bin/wkhtmltoimage-amd64-osx```

```vendor/bin/wkhtmltoimage-amd64-centos6```

```vendor/bin/wkhtmltoimage-i386-centos6```

```vendor/bin/wkhtmltoimage-linux-precise-amd64```

```vendor/bin/wkhtmltoimage-linux-precise-i386```

```vendor/bin/wkhtmltoimage-linux-trusty-amd64```

```vendor/bin/wkhtmltoimage-linux-trusty-i386```

```vendor/bin/wkhtmltoimage-linux-wheezy-amd64```

```vendor/bin/wkhtmltoimage-linux-wheezy-i386```

```vendor/bin/wkhtmltopdf-amd64-osx```

```vendor/bin/wkhtmltopdf-amd64-centos6```

```vendor/bin/wkhtmltopdf-i386-centos6```

```vendor/bin/wkhtmltopdf-linux-precise-amd64```

```vendor/bin/wkhtmltopdf-linux-precise-i386```

```vendor/bin/wkhtmltopdf-linux-trusty-amd64```

```vendor/bin/wkhtmltopdf-linux-trusty-i386```

```vendor/bin/wkhtmltopdf-linux-wheezy-amd64```

```vendor/bin/wkhtmltopdf-linux-wheezy-i386```

Enjoy the bin files!

## ** Disclaimer **

This package is HUGE. It's probably better to grab the individual binaries on a case by case basis:

[wkhtmltopdf OSX](https://github.com/profburial/wkhtmltopdf-binaries-osx)

```js
{
    "require": {
        "profburial/wkhtmltopdf-binaries-osx": "1.0"
    }
}
```

[wkhtmltopdf Cento6](https://github.com/profburial/wkhtmltopdf-binaries-centos6)

```js
{
    "require": {
        "profburial/wkhtmltopdf-binaries-centos6": "1.0"
    }
}
```

[wkhtmltopdf Ubuntu 12.04 (precise)](https://github.com/profburial/wkhtmltopdf-binaries-precise)

```js
{
    "require": {
        "profburial/wkhtmltopdf-binaries-precise": "1.0"
    }
}
```

[wkhtmltopdf Ubuntu 14.04 (trusty)](https://github.com/profburial/wkhtmltopdf-binaries-trusty)

```js
{
    "require": {
        "profburial/wkhtmltopdf-binaries-trusty": "1.0"
    }
}
```

[wkhtmltopdf Debian Wheezy](https://github.com/profburial/wkhtmltopdf-binaries-wheezy)

```js
{
    "require": {
        "profburial/wkhtmltopdf-binaries-wheezy": "1.0"
    }
}
```