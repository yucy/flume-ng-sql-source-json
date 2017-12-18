# flume-ng-sql-source-json
这个项目是改造于https://github.com/keedio/flume-ng-sql-source.git
因keedio的插件flume-ng-sql-source只支持csv的格式，如果数据库表增减字段，则会给开发者造成很大的困扰。所以我添加了一个分支版本，用来将数据以JSON的格式，同步到kafka，字段语义更加清晰。

部署方式和flume-ng-sql-source的一致，参照：http://www.cnblogs.com/yucy/p/7845105.html
