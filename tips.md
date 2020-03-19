此页面最近一次更新时间：2020.03.19                 
[返回到首页](https://passwallopenwrt.github.io/website/)                 
* 开源项目，没有团队负责内测，每次提交完代码都是大家公测。你能正常用老版本就没必要追更新！
* 不保留配置升级：[图文](./upgrade.md)                 
* 请务必保持启用passwall的高级设置里的守护进程！      
* 在passwall插件运行中状态下，如果修改LAN口的静态IP，可能会导致无法上网。重启passwall插件或者重启固件即可解决！         
* 不允许访客使用代理、自由指定不同客户端使用不同线路、盒子看Netflix：[教程](https://youtu.be/qkga9DN5H08)             
* passwall的负载均衡：[教程](https://youtu.be/TRdOfTykgRw)        
* passwall的DNS劫持已经默认由防火墙自定义规则实现了，已经默认劫持了！              
* PassWall+SmartDNS+ChinaDNS-NG搭配：[教程](https://youtu.be/vqAeeLbqvOs)         
* 如何DDNS外网无需加端口远程访问 dynuDNS解析 URL转发 治愈强迫症：[教程](https://youtu.be/c4HSZzTM7G0)         
* 单线or双线，最简单的iptv内网融合教程，需要懂一点基础：[教程](https://github.com/luckyyyyy/blog/issues/44)                  
* 手动单独更新passwall按钮不要一直使用，当出问题后还是需要完整不保留配置刷入最新完整固件的，否则依赖包不会更新，无法修复bug和获得优化体验        
* 如果出现YouTube等一些网站的页面上的特定内容错误显示，比如广告区域加载失败，只有框框没有图片，大概率是你的系统（不是固件！）的负责域名快速解析的HOSTS文件在作妖，解决办法是删除HOSTS文件里的所有规则（# 号注释掉的内容可以不管，其他的都删掉）                               
* 始终无法连接到软路由网络、始终无网络：[可能解决办法](./winproxy.md)               
* 测速：[注意事项](./speed.md)        
* ipv6：[注意事项](./ipv6.md)         
* upnp：如果无法使用，尝试“启用 IGDv1 模式”勾选                 
* 多线多拨：如果失败，尝试“使用旧的macvlan创建方式”勾选                
* 小提示：使用负载均衡同样可以实现故障切换的功能                         
* passwall的恢复默认配置方法：地址栏输入例：                      
  http://192.168.1.1/cgi-bin/luci/admin/vpn/passwall/reset_config                   
  passwall的隐藏菜单方法：地址栏输入例：                 
  http://192.168.1.1/cgi-bin/luci/admin/vpn/passwall/hide                            
  当你隐藏后想再次显示，地址栏输入例：                  
  http://192.168.1.1/cgi-bin/luci/admin/vpn/passwall/show        
* WIFI信号觉得不好？：首先请关闭使用5G优选（智能选频），然后2.4G信号锁死在20MHz，5G信号锁死在你的手机等设备支持到的最高的即可（最近160MHz的也都开始普及了...），这样你离天线远时手动连2.4G信号，离得近时手动连5G信号                  
* 基于Chromium内核的浏览器建议关闭QUIC：[教程](https://www.echoteen.com/turnoff-quic.html)               
* 修改win10的tcp配置参数来提升打开youtube的速度：[教程](https://bincode.cc/ssr-win10-tcp-youtube-speed/)                

