# PostgreSQL示例数据库

**简介**：在本教程中，我们将向您介绍一个PostgreSQL示例数据库，可用于学习和练习PostgreSQL。

*我们将使用DVD出租数据库来演示PostgreSQL的功能。*

DVD出租数据库代表DVD出租商店的业务流程。DVD出租数据库具有许多对象，包括：
·        15 张表
·        1个触发器
·        7 浏览
·        8个功能
·        1个网域
·        13个序列

## DVD租赁ER型号
![[Pasted image 20220919103450.png]]

## PostgreSQL示例数据库表

DVD Rental数据库中有15个表
·        actor-存储角色数据，包括名字和姓氏。
·        film–存储电影数据，例如标题，发行年份，时长，等级等。
·        film_actor –存储电影和角色之间的关系。
·        category–存储电影的类别数据。
·        film_category-存储电影和类别之间的关系。
·        store–包含商店数据，包括经理人员和地址。
·        inventory–存储库存数据。
·        rental–存储租赁数据。
·        payment-存储客户的付款。
·        staff–存储人员数据。
·        customer–存储客户数据。
·        address–存储员工和客户的地址数据
·        city–存储城市名称。
·        country-存储国家名称。

## 下载PostgreSQL示例数据库

您可以通过以下链接下载PostgreSQL DVD Rental示例数据库：[下载DVD租赁样本数据库](https://sp.postgresqltutorial.com/wp-content/uploads/2019/05/dvdrental.zip)
数据库文件的zip格式为（dvdrental.zip），因此dvdrental.tar 在将示例数据库加载到PostgreSQL数据库服务器之前，需要将其解压缩。

## 下载可打印的ER图

除了示例数据库外，我们还为您提供PDF格式的可打印ER图。您可以在练习PostgreSQL的同时下载并打印ER图以供参考。
[下载可打印的ER图](https://sp.postgresqltutorial.com/wp-content/uploads/2018/03/printable-postgresql-sample-database-diagram.pdf)本教程向您介绍了名为DVD Rental的PostgreSQL示例数据库。我们将在我们的PostgreSQL教程中使用此数据库，因此请确保您将其存储在服务器上。
[postgresql](https://www.modb.pro/tag/postgresql?type=knowledge)