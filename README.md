# FortuneSalmonForm

# ローカルのファイルシステムで実行する場合
クロスドメイン制約に引っかかるので以下のように解決する

## Macの場合

```
open /Applications/Google\ Chrome.app/ --args --disable-web-security
```

## Windowsの場合

```
chrome.exe --disable-web-security
```

