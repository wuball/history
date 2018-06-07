### windows 远程错误

[解决方案](https://support.microsoft.com/en-hk/help/4295591/credssp-encryption-oracle-remediation-error-when-to-rdp-to-azure-vm)
>   run `gpedit.msc`    
>   browse to `Computer Configuration > Administrative Templates > System > Credentials Delegation`     
>   Change the `Encryption Oracle Remediation policy` to `Enabled`, and then change `Protection Level` to `Vulnerable`