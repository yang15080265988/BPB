原项目地址 https://github.com/bia-pain-bache/BPB-Worker-Panel
视频教程 https://www.youtube.com/watch?v=5uQB1BaevP0
BPB-Worke-Panel最新版更新工作流
BPB Panel在Cloudflare page上部署并实时更新！源代码



Cloudflare 部署
•创建pages：点击workers和pages，选择pages部署。连接github仓库，选择新建的项目仓库，然后点击部署。

•绑定自定义域名：以防止page分配的域名被屏蔽。

•设置变量：UUID，PROXY_IP, TR_PASS

•绑定KV命名空间：名称随便但不能含有bpb等敏感词

•重试部署pages

BPB面板设置
•部署成功后，打开浏览器输入:https://[自定义域名]/panel检查是否能正常访问BPB面板.

•修改BPB面板密码

•配置BPB面板参数

常用IP获取方式
cleanIP/优选IP：地址1  地址2  地址3  地址4

PROXYIP：
点击进入1 https://www.nslookup.io/domains/bpb.yousef.isegaro.com/dns-records/#authoritative


点击进入2 https://ipdb.030101.xyz/bestproxy/
