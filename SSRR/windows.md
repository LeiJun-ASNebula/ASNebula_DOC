* ### 下载及安装
  * 下载请 [点此跳转到下载中心](SSRR/download.md)

* ### 获取订阅

此处将显示您的订阅链接，请注意为登录状态：

[cinwell website](/sublink?type=ssr ':include :type=markdown')

!> 这个 **订阅链接** 非常重要，你应当把它当做密码一样妥善保管。

* ### 配置

1. 下载、解压、启动三步走策略╮(╯▽╰)╭
2. 进入解压后的`ShadowsocksR-win-4.9.2`文件夹
3. Windows 7及以下系统请启动`ShadowsocksR-dotnet2.0.exe`，Windows 8及以上系统请启动`ShadowsocksR-dotnet4.0.exe`
<center><img src="https://img.asnet.ga/i/2020/03/19/1w4oz2.png"></center>
	* 期间可能会有防火墙的提示，请选择`允许访问`。
4. 设置服务器订阅
	* 右键右下角托盘处的白色小飞机图标→服务器订阅→SSR服务器订阅设置
<center><img src="https://img.asnet.ga/i/2020/03/19/1wrild.png"></center>
	* 先点击Add，再将上面得到的订阅地址复制进`网址`栏，点击确定。
	* 注意： 一定要确保将订阅地址复制进`网址`栏，替换掉默认的地址。
<center><img src="https://img.asnet.ga/i/2020/03/19/1yc7lw.png"></center>
	* 右键小飞机→服务器订阅→更新SSR服务器订阅（不通过代理）
5. 之后，便可以选择节点用了（图例是很早以前的了，目前不止这么点节点）
<center><img src="https://img.asnet.ga/i/2020/03/19/206393.png"></center>
	* 客户端默认开启负载均衡，意思是将流量分配到不同的节点上，由于目前这个功能不是很完善，建议关闭这个功能。（将负载均衡的对勾去掉即可）
<center><img src="https://img.asnet.ga/i/2020/03/19/21kxhf.png"></center>
6. 选择代理模式
	* 推荐设置：平时使用PAC模式，只代理常见被墙网站，当需要代理没有被墙的网站或者不常见的被墙网站时切换成全局模式，使用完后切换回PAC模式。
	* PAC模式
		* 此模式只代理常见被墙网站
		* 右键小飞机→系统代理模式→PAC模式
		* 第一次使用需要更新PAC
			* 右键小飞机→PAC→更新PAC为GFWList
			* 如果你是墙外用户，想要翻回墙内，请选择更新PAC为仅通过大陆常见域名（国外访问大陆）。
	* 全局模式
		* 此模式代理所有国外网站
		* 如果使用此模式时遇到打开国内网站慢的情况，请使用PAC模式，并在需要时在两种模式间切换。
		* 右键小飞机→系统代理模式→全局模式
			* 如果是跳过国内网站，请 右键小飞机→代理规则→绕过局域网和大陆
			* 如果是要翻回墙内，请 右键小飞机→代理规则→绕过局域网和非大陆。  
7. 使用SOCKS5代理
	* 本地使用
		* 软件运行时提供一个本地SOCKS5代理，地址为127.0.0.1，端口为1080。如果你的软件支持使用SOCKS5代理，便可设置使用。此处以Telegram为例
<center><img src="https://img.asnet.ga/i/2020/03/19/27ub0n.png"></center>
8. 更多经验等待你的发掘~kia~