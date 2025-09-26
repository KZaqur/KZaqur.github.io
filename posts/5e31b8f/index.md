# Windows11 如何关闭自动更新


## 前言

因为有些软件及插件，因 Windows11 的更新导致无法使用，故编写此教程。

### 打开注册表

Win&#43;R，输入 regedit，到 HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\WindowsUpdate\UX\Settings 目录下，如图所示

![1](/images/Windows11_update/1.png)

右键新建一个 DWORD 类型的值，名为 `FlightSettingsMaxPauseDays`，如图所示

![2](/images/Windows11_update/2.png)

右键修改，选择10进制，数据改为 2048，如图所示

![3](/images/Windows11_update/3.png)

最后我们在设置，Windows 更新中选择暂停更新时长，如图拉到底选择最长，这样就关闭了 Windows11 自动更新。

![4](/images/Windows11_update/4.png)


---

> Author: [Auseper](https://github.com/KZaqur)  
> URL: https://kzaqur.github.io/posts/5e31b8f/  

