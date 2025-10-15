## 【原创】springboot+vue前后端分离的药材销售管理系统设计与实现

## 系统介绍

基于SpringBoot+Vue前后端分离的药材销售管理系统，系统包含管理员、采销员、库管员角色，功能如下：
- 管理员：首页统计；用户管理；仓库管理；药品管理（药品分类；药品管理）；入库管理（采购清单、入库申请审核、供应商）；
出库管理（订单记录审核、客户管理）；留言反馈；公告管理；个人信息；密码修改；
- 采购员：药品管理（查看药品信息）；入库申请（提交入库申请等待管理员审核）；出库管理（提交订单等待管理员审核）；留言反馈；公告信息；个人信息密码修改。
- 库管员：药品管理（查看药品信息）；入库申请（管理员审核通过之后进行入库操作、供应商）；出库管理（订单被管理员审核通过之后进行出库操作、客户）；留言反馈；公告信息；个人信息密码修改。
主要流程是，管理员生成采购单，然后采销员根据采购单采购药材提交入库申请，由管理员审核通过后在由库管员进行入库操作；药材销售时，由采销员提交销售单，在由管理员审核通过后，由库管员进行出库操作。
系统界面美观大方，功能丰富，使用了SpringBoot、Vue、ElementUI、Echarts等技术栈，适合作为毕业设计、课程设计，有需要可提供指导。

项目由本人原创开发，经过多次测试，项目运行无问题，请放心使用，作者QQ：1344127185。

## 使用技术

服务器端技术栈：

- Springboot
- SpringMvc
- Mybatis
- MySQL

前端技术栈：

- vue
- elementUI
- axios
- echarts

## 环境介绍

- IDEA集成环境
- JDK1.8
- MySQL5.6+

可提供所有运行软件、远程安装、技术指导。

## 运行截图：
![](https://github.com/itcoderyhl/drug-server/blob/main/images/1.png)
![](https://github.com/itcoderyhl/drug-server/blob/main/images/2.png)
![](https://github.com/itcoderyhl/drug-server/blob/main/images/3.png)
![](https://github.com/itcoderyhl/drug-server/blob/main/images/4.png)
![](https://github.com/itcoderyhl/drug-server/blob/main/images/5.png)
![](https://github.com/itcoderyhl/drug-server/blob/main/images/6.png)
![](https://github.com/itcoderyhl/drug-server/blob/main/images/7.png)
![](https://github.com/itcoderyhl/drug-server/blob/main/images/8.png)
![](https://github.com/itcoderyhl/drug-server/blob/main/images/9.png)
![](https://github.com/itcoderyhl/drug-server/blob/main/images/10.png)
![](https://github.com/itcoderyhl/drug-server/blob/main/images/11.png)
![](https://github.com/itcoderyhl/drug-server/blob/main/images/12.png)
![](https://github.com/itcoderyhl/drug-server/blob/main/images/13.png)
![](https://github.com/itcoderyhl/drug-server/blob/main/images/14.png)
![](https://github.com/itcoderyhl/drug-server/blob/main/images/15.png)
![](https://github.com/itcoderyhl/drug-server/blob/main/images/16.png)
![](https://github.com/itcoderyhl/drug-server/blob/main/images/17.png)
![](https://github.com/itcoderyhl/drug-server/blob/main/images/18.png)
![](https://github.com/itcoderyhl/drug-server/blob/main/images/19.png)
![](https://github.com/itcoderyhl/drug-server/blob/main/images/20.png)
![](https://github.com/itcoderyhl/drug-server/blob/main/images/21.png)
![](https://github.com/itcoderyhl/drug-server/blob/main/images/22.png)
![](https://github.com/itcoderyhl/drug-server/blob/main/images/23.png)
![](https://github.com/itcoderyhl/drug-server/blob/main/images/24.png)
