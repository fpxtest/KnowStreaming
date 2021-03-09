
---

![kafka-manager-logo](./docs/assets/images/common/logo_name.png)

**一站式`Apache Kafka`集群指标监控与运维管控平台**

--- 

## v2.3.0

版本上线时间：2021-02-08


### 能力提升

- 新增支持docker化部署
- 可指定Broker作为候选controller
- 可新增并管理网关配置
- 可获取消费组状态
- 增加集群的JMX认证  

### 体验优化

- 优化编辑用户角色、修改密码的流程
- 新增consumerID的搜索功能
- 优化“Topic连接信息”、“消费组重置消费偏移”、“修改Topic保存时间”的文案提示
- 在相应位置增加《资源申请文档》链接 

### bug修复

- 修复Broker监控图表时间轴展示错误的问题
- 修复创建夜莺监控告警规则时，使用的告警周期的单位不正确的问题



## v2.2.0

版本上线时间：2021-01-25



### 能力提升

- 优化工单批量操作流程 
- 增加获取Topic75分位/99分位的实时耗时数据
- 增加定时任务，可将无主未落DB的Topic定期写入DB

### 体验优化

- 在相应位置增加《集群接入文档》链接
- 优化物理集群、逻辑集群含义
- 在Topic详情页、Topic扩分区操作弹窗增加展示Topic所属Region的信息
- 优化Topic审批时，Topic数据保存时间的配置流程
- 优化Topic/应用申请、审批时的错误提示文案
- 优化Topic数据采样的操作项文案
- 优化运维人员删除Topic时的提示文案
- 优化运维人员删除Region的删除逻辑与提示文案
- 优化运维人员删除逻辑集群的提示文案
- 优化上传集群配置文件时的文件类型限制条件

### bug修复

- 修复填写应用名称时校验特殊字符出错的问题
- 修复普通用户越权访问应用详情的问题
- 修复由于Kafka版本升级，导致的数据压缩格式无法获取的问题
- 修复删除逻辑集群或Topic之后，界面依旧展示的问题
- 修复进行Leader rebalance操作时执行结果重复提示的问题


## v2.1.0

版本上线时间：2020-12-19



### 体验优化

- 优化页面加载时的背景样式
- 优化普通用户申请Topic权限的流程
- 优化Topic申请配额、申请分区的权限限制
- 优化取消Topic权限的文案提示
- 优化申请配额表单的表单项名称
- 优化重置消费偏移的操作流程
- 优化创建Topic迁移任务的表单内容
- 优化Topic扩分区操作的弹窗界面样式
- 优化集群Broker监控可视化图表样式
- 优化创建逻辑集群的表单内容
- 优化集群安全协议的提示文案

### bug修复

- 修复偶发性重置消费偏移失败的问题



