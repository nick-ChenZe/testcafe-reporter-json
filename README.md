# testcafe-reporter-json
[![Build Status](https://travis-ci.org/DevExpress/testcafe-reporter-json.svg)](https://travis-ci.org/DevExpress/testcafe-reporter-json)

This is the **JSON** reporter plugin for [TestCafe](http://devexpress.github.io/testcafe).

<p align="center">
    <img src="https://raw.githubusercontent.com/DevExpress/testcafe-reporter-json/master/media/preview.png" alt="preview" />
</p>

## Install

This reporter is shipped with TestCafe by default. In most cases, you won't need to install it separately.

However, if you need to install this reporter, you can use the following command.

```
npm install testcafe-reporter-json
```

## Usage

When you run tests from the command line, specify the reporter name by using the `--reporter` option:

```
testcafe chrome 'path/to/test/file.js' --reporter json
```


When you use API, pass the reporter name to the `reporter()` method:

```js
testCafe
    .createRunner()
    .src('path/to/test/file.js')
    .browsers('chrome')
    .reporter('json') // <-
    .run();
```

## Author
Developer Express Inc. (https://devexpress.com)
