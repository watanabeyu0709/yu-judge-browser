## Introduce
this is a simple script use useragent to judge browser

## Quick to start
Using npm:
```shell
$ npm install --save yu-judge-browser
$ import browser from 'yu-judge-browser'
```

## Example
```js
    console.log(browser)

    {
        "versions":{
            "trident":false,
            "presto":false,
            "webKit":true,
            "gecko":false,
            "mobile":false,
            "ios":false,
            "android":false,
            "iPhone":true,
            "iPad":false,
            "qq":false,
            "wechat":false,
            "webApp":false
        },
        "language":"zh-cn"
    }"
 ```

## JSDoc
```jsdoc
 * @returns {object[]} versions - true or false of different terminals
 * @returns {boolean} [versions[].trident] - is ie ?
 * @returns {boolean} [versions[].presto] - is opera ?
 * @returns {boolean} [versions[].AppleWebKit] - is apple,chrome ?
 * @returns {boolean} [versions[].gecko] - is firefox ?
 * @returns {boolean} [versions[].mobile] - is mobile ?
 * @returns {boolean} [versions[].ios] - is ios ?
 * @returns {boolean} [versions[].android] - is android ?
 * @returns {boolean} [versions[].iPhone] - is iPhone ?
 * @returns {boolean} [versions[].iPad] - is iPad ?
 * @returns {boolean} [versions[].qq] - is qq browser ?
 * @returns {boolean} [versions[].wechat] - is wechat browser ?
 * @returns {boolean} [versions[].webApp] - is webApp ?
 * @returns {string} language - language of this web
```

## Links
[![github](http://p0kpwl4c8.bkt.clouddn.com/icon/github_c.png!icon_sm "https://github.com/watanabeyu0709/yu-judge-browser")](https://github.com/watanabeyu0709/yu-judge-browser)
[![npm](http://p0kpwl4c8.bkt.clouddn.com/icon/npm_c.png!icon_sm "https://www.npmjs.com/package/yu-judge-browser")](https://www.npmjs.com/package/yu-judge-browser)
