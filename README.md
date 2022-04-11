<div align=center><img width="240" height="240" alt="Logo was Loading Faild!" src="https://raw.githubusercontent.com/hacku7/gopay/main/logo.png"/></div>

# GoPay

### 微信、支付宝、PayPal、QQ 的 Golang 版本SDK

<br>
# 一、安装

```bash
go get -u github.com/hacku7/gopay
```

#### 查看 GoPay 版本

  [版本更新记录](https://github.com/hacku7/gopay/blob/main/release_note.txt)

```go
import (
    "github.com/hacku7/gopay"
    "github.com/hacku7/gopay/pkg/xlog"
)

func main() {
    xlog.Info("GoPay Version: ", gopay.Version)
}
```

---

<br>

# 二、文档目录

> ### 点击查看不同支付方式的使用文档。方便的话，请留下您认可的小星星，十分感谢！

* #### [Alipay](https://github.com/hacku7/gopay/blob/main/doc/alipay.md)
* #### [Wechat](https://github.com/hacku7/gopay/blob/main/doc/wechat_v3.md)
* #### [QQ](https://github.com/hacku7/gopay/blob/main/doc/qq.md)
* #### [Paypal](https://github.com/hacku7/gopay/blob/main/doc/paypal.md)
* #### [Apple](https://github.com/hacku7/gopay/blob/main/doc/apple.md)

---

<br>

# 三、其他说明
* 各支付方式接入，请仔细查看 `xxx_test.go` 使用方式
    * `gopay/wechat/v3/client_test.go`
    * `gopay/alipay/client_test.go`
    * `gopay/qq/client_test.go`
    * `gopay/paypal/client_test.go`
    * `gopay/apple/verify_test.go`
    * 或 examples
  
  ```
<br>