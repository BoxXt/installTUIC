# TUIC 小白一键安装脚本（目前仅提供meta客户端使用的配置文件）
## 物料准备
* 一台vps
* 一个dns解析到此vps ip的域名


## 如何使用脚本
* 登录vps
* 输入以下指令,并按照指令提示操作即可
  ```
  sudo curl -o installTUIC.sh https://raw.githubusercontent.com/BoxXt/installTUIC/main/installTUIC.sh && sh ./installTUIC.sh
  ```
* 最终得到 Meta 的客户端配置文件，选用支持 Clash.meta 的客户端导入使用即可


## 客户端
  能力有限目前暂时支持输出clash.meta客户端配置给到meta客户端使用，可使用客户端列表（待测试补充）：
  * macOS:
  [ClashX.Meta](https://github.com/MetaCubeX/ClashX.Meta/releases/tag/v1.2.1)
    * 需要更新内核版本为alpha最新版本。
    
  * Windows:
  [Clash Verage](https://github.com/zzzgydi/clash-verge/releases/tag/v1.2.3)
    * 需要更新内核版本为alpha最新版本。
    
  * iOS:
    * [Singbox]() 
      * 需要自己手搓Singbox客户端配置。  
    * [Pharos Pro]()
      * 商店版本在1.7.9以上可用。
  
  * Android:
    [ClashMetaForAndroid](https://github.com/MetaCubeX/ClashMetaForAndroid/releases/tag/Prerelease-alpha)
    * 需要更新至最新版本。









## 鸣谢
* cnmeeia ：https://github.com/cnmeeia/shell
