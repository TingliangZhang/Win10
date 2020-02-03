# Win10
Win10笔记

## [如何设置使wifi热点随系统开机自动启动](https://answers.microsoft.com/zh-hans/windows/forum/all/%E5%A6%82%E4%BD%95%E8%AE%BE%E7%BD%AE%E4%BD%BFwifi/c8317d49-6c5d-49e0-bc0b-4dea2f4a1d0c)

1.小娜搜索“服务”，并打开

2.在列表中找到“Windows 移动热点服务”

3.右击“Windows 移动热点服务”，打开属性

4.在“常规”选项卡中，把这项服务的启动类型改成“自动”，并启动这个服务项。

如果需要改回手动启动，重复上述步骤1~3，然后在步骤4中把启动类型改成手动即可。

## OpenVPN 开机[自动登录](https://www.jinbo123.com/3376.html)

修改快捷方式的属性，"C:\Program Files\OpenVPN\bin\openvpn-gui.exe" --connect skyworks-campus-ipv4-windows.ovpn