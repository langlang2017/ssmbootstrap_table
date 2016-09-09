#ssmbootstrap_table demo
## 技术栈
* spring+springmvc+jdbcTemplate
* bootstrap3/bootstrap-table1.9
* druid/fastjson
* log4jdbc
* hibernate-validator
* [urlrewrite](http://tuckey.org/urlrewrite/)
* Jcaptcha
* `shiro`

##How to run
项目采用maven构建，运行前请先执行src/main/java下的sql脚本到你的mysql数据库中，然后修改src/main/resource下的jdbc.properties配置文件中的数据库配置信息，进入项目目录，执行mvn tomcat7:run来运行
