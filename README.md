# CVE-2020-1472 POC
Requires the latest impacket from [GitHub](https://github.com/SecureAuthCorp/impacket) with added netlogon structures.

Do note that by default this changes the password of the domain controller account. Yes this allows you to DCSync, but it also breaks communication with other domain controllers, so be careful with this!

More info and original research [here](https://www.secura.com/blog/zero-logon)