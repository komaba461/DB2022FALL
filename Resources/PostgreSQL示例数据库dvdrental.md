# PostgreSQL示例数据库

**简介**：在本教程中，我们将向您介绍一个 PostgreSQL 示例数据库，可用于学习和练习PostgreSQL。

*我们将使用 DVD 出租数据库来演示 PostgreSQL 的功能。*

DVD 出租数据库代表 DVD 出租商店的业务流程。DVD 出租数据库具有许多对象，包括：
| 15 张表      | 1个触发器 | 7 浏览 | 8个功能 | 1个网域 | 13个序列 |
| ----------- | -------- | ----- | ------ | ------ | ------- |
## DVD租赁ER型号
![](https://obs-emcsapp-public.obs.cn-north-4.myhwclouds.com/image%2Feditor%2F8227cb7d-c961-4600-b61f-97d0aada93ba.png)

## PostgreSQL示例数据库表

DVD Rental数据库中有15个表
| actor| film | film_actor | category | film_category | store | inventory | rental | payment | staff | customer | address | city | country |
| ----------------------- | --------------------------------------- | -------------------- | --------------- | -------------------- | -------------------------- | ----------- | --------- | ------------ | ---------- | ---------- | -------------------- | ---------- | ------- |
| 存储角色数据，包括名字和姓氏 | 存储电影数据，例如标题，发行年份，时长，等级等 | 存储电影和角色之间的关系 | 存储电影的类别数据 | 存储电影和类别之间的关系 | 包含商店数据，包括经理人员和地址 | 存储库存数据 | 存储租赁数据 | 存储客户的付款 | 存储人员数据 | 存储客户数据 | 存储员工和客户的地址数据 | 存储城市名称 | 存储国家名|

## 下载PostgreSQL示例数据库

您可以通过以下链接下载 PostgreSQL DVD Rental 示例数据库：[下载DVD租赁样本数据库](https://postgresqltutorial.com/wp-content/uploads/2019/05/dvdrental.zip)
数据库文件的zip格式为（dvdrental.zip），因此 dvdrental.tar 在将示例数据库加载到 PostgreSQL 数据库服务器之前，需要将其解压缩。

## 下载可打印的ER图

除了示例数据库外，我们还为您提供 PDF 格式的可打印ER图。您可以在练习 PostgreSQL 的同时下载并打印ER图以供参考。
[下载可打印的ER图](https://postgresqltutorial.com/wp-content/uploads/2018/03/printable-postgresql-sample-database-diagram.pdf) 本教程向您介绍了名为 DVD Rental 的 PostgreSQL 示例数据库。我们将在我们的 PostgreSQL 教程中使用此数据库，因此请确保您将其存储在服务器上。

[原文链接](https://www.modb.pro/db/27910)