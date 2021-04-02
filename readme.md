# 云开发短信验证码扩展最佳实践｜预约、登录、验真场景

## 项目介绍

云开发推出短信验证码扩展能力，可以免复杂的接入轻松和云开发登录等体系对接，本项目以一个预约场景，需要手机号验证来出发，依靠云开发做的应用。

![应用最终状态](https://main.qcloudimg.com/raw/e41ed99ab4615ce3551a2d196e78c703.png)

## 使用步骤

1. 前往[云开发控制台-扩展应用](https://console.cloud.tencent.com/tcb/extensions/index)下，安装短信验证码扩展能力

![](https://main.qcloudimg.com/raw/2534f3ba82453bf53acc78aca2e237b2.png)

在第4步操作步骤中，按如下图所示配置

![](https://main.qcloudimg.com/raw/183097de731ef4eb4271217ac08a3abc.png)

等待扩展应用安装完毕即可

2. 前往[云开发控制台-数据库](https://console.cloud.tencent.com/tcb/db/index)下，创建名为SIGN的数据库，默认权限即可。

3. 下载项目代码，在webviews/sign/index.js中，第一行，关键文字中更改如下为自己的环境ID（一定要和前几步操作保持相同的环境ID）
   
4. 如果你要在本地去进行测试，要设置本地安全域名；预约的记录可以在数据库中SIGN集合找到，可以自己按照需要制作应用，或者使用CMS内容管理系统扩展能力。

## 项目作者

- 云开发团队zirali