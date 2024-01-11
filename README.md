快速构建c3p0
c3p0-spring-boot-starter
- autoconfigure ：包含功能类与自动配置代码
- starter:此模块没有代码，主要是进行pom的依赖设定，以确保功能库能正确使用
用上了DataSourceProperties，这样就可以直接使用过spring.datasource前缀进行连接相关信息的配置了
