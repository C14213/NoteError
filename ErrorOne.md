public和protected字段 ** 首字母大写 **<br>
private字段** 下划线字母小写 **<br>
### 做项目要有思路，先干什么再干什么，代码习惯要跟据公司的来，把以前不一样的抛掉
复习一遍：<br>
1.CodeFirst:建立Model,安装EntityFramework<br>，编写上下文（遵守约定大于配置的原则）
** 注意 ** model不能建立在MVC项目里的model，mvc里的model是跟ui相关的，若把实体类放到mvc的model里会有风险，因为一旦ui有变化，就全部都要改了<br>
实体类里的字段跟据需求来，有无关联关系，起名有无符合代码规范，是不是所有都注释上了，还要代码的折叠，讲究可读性可维护性
2.codefirst之数据迁移
3.codefirst+fluentAPI
4.三层架构+DTO
5.依赖注入、IOC(Autofac)、仓储层，注入不加注释，其他一律加注释、微软unity
