### windows 远程错误

[解决方案](https://support.microsoft.com/en-hk/help/4295591/credssp-encryption-oracle-remediation-error-when-to-rdp-to-azure-vm)
>   run `gpedit.msc`    
>   browse to `Computer Configuration > Administrative Templates > System > Credentials Delegation`     
>   Change the `Encryption Oracle Remediation policy` to `Enabled`, and then change `Protection Level` to `Vulnerable`


### 微信
微信支付结果通知地址不支持 https


### dotnet
发布 debug 版本，调试附加至对应 dotnet 进程，可调试外部网址（案例：调试微信支付结果通知）



