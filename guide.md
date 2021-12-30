# 快速入门


## 请您提前确认

- 已注册UCloud账号。[点击快速注册](https://passport.ucloud.cn/#register) 或 *直接联系您的客户经理*    

- UCloud账号已通过企业实名认证。[点击账号实名认证](https://console.ucloud.cn/uaccount/authentication)

![UNVS号码认证服务_快速入门](../unvs/images/guide/UNVS号码认证服务_快速入门指南V1.0.png)


### **1. 开通号码认证服务**

- 登陆UCloud账号，选择号码认证服务，[访问控制台- UNVS号码认证服务](https://console.ucloud.cn/unvs) 
- 点击阅读并同意《UCloud号码认证服务开通协议》


### **2. 新建应用**

号码认证服务调用前，需要您在控制台提交对应移动端的应用及资质信息，我们将同步提交至运营商进行应用报备，报备通过后，即可正常使用；

- **申Andorid应用申请**：您需要提供应用的包名、包签名( 包签名计算方式 见下述)及应用归属企业资质，[点击申请应用](https://console.ucloud.cn/unvs/application)；
- **申请iOS应用申请**：您需要提供应用的BundleID及应用归属企业资质，[点击申请应用](https://console.ucloud.cn/unvs/application)；
- **Andorid应用签名计算方式**：
  - 下载签名获取工具APP并在Andorid手机上安装；
    - a）国密算法包签名生成工具；
    - b）非国密算法包签名生成工具；
  - 在手机上安装开发者的应用；
  - 启动签名获取工具APP，输入开发者的应用APP包名，点击“获取包签名”；



### **3. 新建业务场景**

您可以根据实际业务需要，申请对应一键登录注册、本机号码认证的各类业务场景，每一个业务场景需要跟应用绑定后方可使用；   
一个业务场景只能绑定一个应用，一个应用可以绑定多个业务场景；

- **配置业务场景**：申请业务场景后，根据实际业务需要，跟应用作关联绑定，[点击配置业务场景](https://console.ucloud.cn/unvs)；





### **4.服务调用&集成**

建议先通过[模拟API接口](https://docs.ucloud.cn/api/unvs-api/index)方式调用进行服务调用测试，调用成功后在对接API或SDK进行联调；

- 对接 **移动前端SDK** 完成移动前端调用测试：[点击使用 移动前端SDK ](https://console.ucloud.cn/unvs) 
- 对接**服务端SDK** 完成服务端调用测试：[点击使用 服务端SDK ](https://console.ucloud.cn/unvs) 



### **5.购买资源包**

已完成实名认证的账号可以购买适量的号码认证服务套餐包进行测试和使用；

- 购买号码认证服务套餐包：[点击购买号码认证服务套餐包](https://console.ucloud.cn/unvs/buy) 


### **6.查询业务数据**

号码认证服务对接使用后，可以通过如下方式查询服务调用相关业务数据：

- 通过 业务数据页 查询：[点击查询 业务数据统计 信息](https://console.ucloud.cn/unvs/application) 

