# dev notes

## webdriver

以下脚本可以用于绕过webdriver检测：

```shell
# generate [stealth.min.js](libs/stealth.min.js)
npx extract-stealth-evasions 
```

使用 undetected_chromedriver 可以基于用户 profile 顺利登陆（todo: 研究其机制）

```shell
# ref: https://stackoverflow.com/a/78006137/9422455
import undetected_chromedriver as uc
```