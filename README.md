## 接毕业设计和论文

### 作者微信：vvsgxmn  (支持修改、 部署调试、 支持代做毕设)

### 接网站建设、小程序

### 选题+开题报告+任务书+程序定制+安装调试+论文+答辩ppt 都可以做

### 购买地址：[https://www.vvxx.love](https://www.vvxx.love)（vv毕设网）

### 支持 **一键生成 UML 图**：上传项目压缩包即可自动产出功能模块图、用例图、流程图、E-R 图、时序图等全套毕设图表。

### 提供 **免费配套软件下载 + 安装说明 + 部署教程**

![vv毕设网 - 一键画图](https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/uml-draw.png)

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/image-20260825133349317.png" alt="image-20260825133349317" />

⚠️ Bug添加微信**免费修复**，免费修复。其他平台的私信一律不管（微信方便发送文件）

---

# 基于SpringBoot+Vue的宠物洗护预约系统

![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white) ![Vue3](https://img.shields.io/badge/-Vue3-grey?style=flat-square) ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MyBatis](https://img.shields.io/badge/-MyBatis-000000?style=flat-square&logo=mybatis&logoColor=white) 

## 项目介绍

本系统是一款面向宠物主和单店洗护门店的预约与履约管理平台。它把容易分散在电话、聊天记录和纸质排班表中的爱宠信息、套餐选择、技师和舱室档期放到同一笔预约里，覆盖在线下单、支付、到店核销、洗护报告和接回确认。宠主可回看进度与养护历史，门店可按日查看工位安排和服务记录。

系统采用 Spring Boot、Vue 和 MySQL，区分宠物主、门店店员、洗护技师与系统管理员。服务端在创建预约时复核同日同档的技师和舱室占用，订单按待支付、待到店、洗护中、待接回和完成流转。系统还提供次卡、优惠券、退款评价及经营看板，适合作为毕业设计或课程设计的门店服务案例；在线支付为模拟，不接入真实支付渠道。

## 主要功能模块

- **登录与角色分流**：统一注册和登录入口，按角色进入宠主门户、门店工作台或管理后台。
- **爱宠档案与养护记录**：维护爱宠品种、体型、疫苗情况和洗护禁忌，并按爱宠查看历史服务报告及前后对比照。
- **套餐与资源浏览**：按分类查看洗护套餐、适用对象与服务工序，同时了解技师资质和舱室类型。
- **在线预约与档期校验**：选择爱宠、套餐、时段、技师、舱室及增值项目，提交时复核同一档期的技师和舱室占用。
- **预约支付与取消**：支持账户余额或模拟在线支付；按订单状态处理取消，保留金额、优惠与履约状态。
- **排班与代客开单**：店员按日期和工位查看预约安排，并为电话或现场来客登记预约。
- **到店核销与服务履约**：以核销码或工单完成签到，记录现场加项和洗护报告，最后由宠主确认接回。
- **次卡与优惠券**：宠主可领券或购买次卡；门店按卡密、有效期与剩余次数核销并留存扣次流水。
- **退款、评价与社区**：宠主可提交退款申请、评价或晒单；管理员处理退款审核、评价回复和社区内容。
- **基础配置与经营看板**：维护套餐、分类、技师舱室与会员，汇总预约量、营收、会员和建档数据供经营查看。

## 技术架构

- **后端**：Spring Boot + MyBatis-Plus + JWT
- **前端**：Vue 3 + TypeScript + Vue Router + Pinia + Element Plus + Vite + ECharts
- **数据库**：MySQL

<!-- screenshots-start -->
## 系统截图

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/petgrooming/%E7%99%BB%E5%BD%95%E9%A1%B5%E9%9D%A2.png" alt="登录页面" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/petgrooming/%E7%94%A8%E6%88%B7%E9%A6%96%E9%A1%B5.png" alt="用户首页" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/petgrooming/%E6%B4%97%E6%8A%A4%E5%A5%97%E9%A4%90.png" alt="洗护套餐" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/petgrooming/%E6%88%91%E7%9A%84%E7%88%B1%E5%AE%A0.png" alt="我的爱宠" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/petgrooming/%E5%9C%A8%E7%BA%BF%E9%A2%84%E7%BA%A6.png" alt="在线预约" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/petgrooming/%E9%97%A8%E5%BA%97%E5%B7%A5%E4%BD%9C%E5%8F%B0.png" alt="门店工作台" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/petgrooming/%E9%A2%84%E7%BA%A6%E6%A0%B8%E9%94%80.png" alt="预约核销" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/petgrooming/%E7%AE%A1%E7%90%86%E5%91%98%E4%BB%AA%E8%A1%A8%E7%9B%98.png" alt="管理员仪表盘" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/petgrooming/%E8%AE%BA%E6%96%87%E5%9B%BE1.png" alt="论文图1" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/petgrooming/%E8%AE%BA%E6%96%87%E5%9B%BE2.png" alt="论文图2" width="600" />

<img src="https://fanhua-yingcai.oss-cn-shanghai.aliyuncs.com/AutoUpload/screenshots/petgrooming/UML%E5%9B%BE%E5%88%97%E8%A1%A8.png" alt="UML图列表" width="600" />

<!-- screenshots-end -->
