## WeiCot ERP  定制类平台 解决方案
项目主页：https://www.weicot.com/
# 捐赠
您的捐赠是对WC2M 项目开发组最大的鼓励和支持。我们会坚持开发维护下去。 您的捐赠将被用于：

  - 持续和深入地开发
  - 文档和社区的建设和维护
  
[捐赠链接](https://www.weicot.com)


####  主开发框架
```
主开发框架
WeiCot Framework (WF)V 2.3
WeiCot Swoole Framework  (WSF)V1.2
WeiCot Design Components  (WDC)V1.6
```

#### 架构思想
> 高可用 高性能 模块化 可拆分 低消耗 分布式 反特征  


#### 系统定位
WeiCot C2M智能供应链平台 以及下一代系统 S2B智能供应链服务平台


#### 系统使命

###### WC2M-C2M 版
```
WC2M 是一种 C2M智能供应链平台， 企业利用智能智造升级传统工厂，通过互联网渠道改变传统消费生产模式，
使产品真正由先生产到消费，转变到先消费后生产。
作为中国领先的C2M智能供应链平台，WC2M 重视柔性化生产和个性化创作，系统目前支持五大品类包含服装、家居、电子周边、鞋帽、箱包等300多款产品可以实现定制化生产。
我们承诺提供合理定价，高品质并且环保安全的产品给我们的消费者。
```
###### WC2M-S2B 版
```
新版 WC2M S2B智能供应链服务平台，通过技术改造传统制造业走向柔性化和智能化生产；实现以零库存帮助创业者提高竞争能力，降低经营风险；
支持一件起定，批发价格帮助内容和流量客户提高变现能力
```

#### 系统组成部分

WeiCot C2M智能供应链平台 以及下一代系统 S2B智能供应链服务平台本平台业务架构体系  由几部分部分组成
```
1.工厂加盟系统
2.业务加盟系统
3.平台加盟系统
4.设计加盟系统
```
采用非常灵活的业务架构 以及高度的标准和专业化  使用以上的资源通过WEICOT CRM 平台系统进行整合并将手中资源在合作中变现


####  系统架构
WEB 端  服务端   远程同步端   反代集群






### WEB 端部分功能概览

##### 设计类系统基础功能
- 账号管理  
- 账号分为4个等级  
- 系统管理账户   （系统的一切事物）
- 工厂账户       （用以添加工厂的 产品模板 以及 管理通过业务系统分发到工厂的 订单等   
- 加盟商账户     （账户可以分组  分业务员  子账号 并在这种等下下共享不同的资源  包括可以设计的产品 以及 图库 订单 等资源等）
- 设计模板上传
- 图片上传
- 设计产品    （选择 设计 效果  合成速度 以及质量等）    带自动居中  自动纠偏 高性能 所有有图案的都支持
- 导出产品
- 导入订单
- 查看订单
- 生产系统
- 由高性能图片引擎 合成工厂图片
- 并将订单信息推送到工厂端  具体的 那个工厂 那个工人 哪台打印机上  并及时反馈生产信息

####  导出支持的平台

- 亚马逊
- wish
- 速卖通
- zencart
- magento
- 等其他第三方电商类平台

#### 支持产品类型
- 全幅  
- 非全幅 
- 多色彩变体 
- 多细节变体

#### 设计器   专业版部分功能

- 1.支持快捷键
- 2.支持常用设计操作
- 3.支持自动纠偏
- 4.支持自动居中
- 5.支持多色彩自动合成
- 6.支持全幅类设计效果图的细节图自动合成
- 7.支持快速设计
- 8.支持设计与生产一体化标准
- 9.支持多面设计 与设计后的多面效果图自动补全
- 10.支持工厂视图合成
- 11.支持工厂视图 自动切分
- 12.支持类3D 多面效自动补全
- 13.支持低性能下快速高质量合成
> 更多请看项目下面的更新日志



### WED 端 与服务端 通讯支持

#### 消息中间件 与队列
支持 简易中间件 w-redis  和 MQ
服务端自带 基于TCP 的 RPC 通讯模块
#### 其他相关
3D 设计器  
以上部分模块已经开源
api  系统
异步 系统

##### 服务端 

- 1.支持RPC 模块调用
- 2.支持并行任务
- 3.支持TCP 服务端
- 4.支持TPC 服务端异步推送以及同步
- 5.支持多进程任务
- 6.支持队列
- 7.支持数据包切分和校验


