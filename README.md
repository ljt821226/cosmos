# cosmos

微服务分布式开发平台是基于spring-boot 2.0进行搭建的微服务分布式开发平台，功能如下： 
<br/>
1、集成CXF实现restful功能，通过自动注解@EntityParam实现json与实体自动转换，支持实体和实体数组； 
<br/>
2、通用实体：类似SOA中的SDO，具备实体和Map双功能，能够在实体、json、map、xml之间自由转换； 
<br/>
3、模拟JTA原理，通过两阶段提交来解决分布式事务问题，实现分布式事务一致性功能，无需要编写业务补偿代码； 
<br/>
4、集成mybatis做持久层，实现自动分页； 
<br/>
5、集成swagger-v3； 
<br/>
6、有后台代码一键生成的eclipse插件；
