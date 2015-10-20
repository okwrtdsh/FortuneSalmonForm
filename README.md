# FortuneSalmonForm

## ローカルのファイルシステムで実行する場合
クロスドメイン制約に引っかかるので以下のように解決する

### Macの場合

```
open /Applications/Google\ Chrome.app/ --args --disable-web-security ./index.html
```

### Windowsの場合

```
chrome.exe --disable-web-security ./index.html
```

## URLを適宜調整
* https://github.com/okwrtdsh/FortuneSalmonForm/blob/master/index.html#L77
* https://github.com/okwrtdsh/FortuneSalmonForm/blob/master/index.html#L131
* https://github.com/okwrtdsh/FortuneSalmonForm/blob/master/index.html#L157
