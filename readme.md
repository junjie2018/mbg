#### 使用方式：

1.打开config.properties修改数据库信息

2.打开config.properties修改entities和mapper的包名

3.打开config.properties修改生成路径，可以直接生成到自己项目中，但是建议不要这么做

4.打开generatorConfig.xml添加需要修改的表

5.点击run.bat运行

#### 研究方向
1.可以继续研究使用java代码的方式使用这个插件，这样就可以脱离ide运行了



#### 个人心得：
1.其实在开发中，这种需求非常少，像我一般都是直接通过写sql和对应的entity

2.在使用通用Mapper时，这个工具还是能起到不小的作用，毕竟通用Mapper很依赖完整的实体类