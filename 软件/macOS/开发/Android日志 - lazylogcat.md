安装：
brew install parfenovvs/lazylogcat/lazylogcat

---

配置：
~/Library/Application Support/lazylogcat/config.json
```json
{
  "$schema": "https://github.com/parfenovvs/lazylogcat/raw/trunk/config.schema.json",
  "filter": {
    "package_name": "com.sinosure"
  }
}
```

~/.zshrc
```shell
alias logcat='lazylogcat'
```
