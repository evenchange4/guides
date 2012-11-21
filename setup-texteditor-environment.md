## 設置編輯器

### Sublime Text2 

下載位址：<http://www.sublimetext.com/2>

#### 安裝 Package Control

<http://wbond.net/sublime_packages/package_control/installation>

之後可以透過 `Cmd` + `Shift` + `p` 叫出來選單。

#### Package Control

`Cmd` + `Shift` + `p` -> `Install ...`

## 必裝 Submlime Text2 套件

* [BeautifyRuby](https://github.com/CraigWilliams/BeautifyRuby)

`Ctrl` + `Cmd` + `k` 自動對 Ruby 縮排 


## 必加設定

`Preferences` -> `Key Bindings - User`

```
  { "keys": ["ctrl+shift+r"], "command": "reindent" , "args": {"single_line": false} }
```

`Ctrl` + `Shift` + `r` 自動對 HTML 縮排 