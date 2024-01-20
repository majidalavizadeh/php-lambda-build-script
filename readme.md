# PHP Binary builder for AWS Lambda

You can build a PHP binary file for AWS Lambda

### Requirements

- Docker

### Run

```bash
sh ./build.sh 8.2.15
```

you need to pass the PHP version to the `build.sh`, you can find the latest PHP versions here:
https://github.com/php/php-src/tags

If you want to optimize the compile to use more jobs have a look in build.sh. You can also change the build arguments,
I want a good foundation for running default laravel.

This package is an improved version of https://github.com/ArtisanHost/php-cgi-lambda-build-script
