* ### 功能
  * 系统代理设置
  * PAC 模式和全局模式
  * GFWList 和用户规则
  * 支持 HTTP 代理
  * 支持多服务器切换
  * 支持 UDP 代理
  * 支持插件

* ### 下载及安装
  * 下载请 [点此跳转到下载中心](SS/download.md)

下载后解压，会解压出一个名为 Shadowsocks 的文件夹。
<center><img src="https://img.asnet.ga/i/2020/03/09/qv24ia.png"></center>
在文件夹里面双击打开 Shadowsocks.exe ，任务栏中会出现一个小飞机。
<center><img src="https://img.asnet.ga/i/2020/03/08/pb83gs.png"></center>

**注：如果无法打开，请确认您的系统为完整原版的Windows，而不是各种的XX花园、雨XX风、XX公司之类的。**

**另外，请确认您的电脑上没有运行360、腾讯电脑管家之类的“杀毒”软件，否则我们保留清退您的权利。**

* ### 导入节点
  1. 点击此处回到 <a href="/user">用户中心</a> ，在快速使用中选择 GENERAL 一栏，点击 SS 类型下的 **全部 URL**。
<center><img src="https://img.asnet.ga/i/2020/03/09/p85loz.png"></center>
  2. 在任务栏中右键单击纸飞机，服务器→从剪切板导入URL
<center><img src="https://img.asnet.ga/i/2020/03/09/pl604e.png"></center>
  3. 在弹出的窗口中删除掉默认的未配置文件。
<center><img src="https://img.asnet.ga/i/2020/03/09/pshj0p.png"></center>
  * 题外话，最新版本的SS似乎不再内置obfs-local插件了，目前需要单独下载。当然，我们也做了整合包。提到的文件均可在 [Shadowsocks各版本下载中心
](SS/download.md) 下载。
  4. 右键单击纸飞机，服务器→你需要使用的节点。
* ### 设置代理
  * 对于SS来说，使用代理方式有三种：禁用、PAC模式、全局模式。
<center><img src="https://img.asnet.ga/i/2020/03/09/r0c8uc.png"></center>
  *启用方法：右键单击纸飞机→系统代理→禁用、PAC模式、全局模式  

> 禁用：顾名思义，就是不使用SS的代理。

> PAC模式：是一种较为智能的代理模式，日常使用推荐这种方式。

> 全局模式：一种较为绝对的模式，在这个模式下所有流量都会通过节点（包括访问国内网站）

