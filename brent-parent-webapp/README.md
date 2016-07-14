#brent-parent-webapp

##工程说明
* 为所有webapp工程提供公共打包配置和常用jar包引用
* 此工程为pom类型，不能直接引用
* 可以为不同环境打出不同配置文件的war包
* 工程根目录下新建profiles/环境profile.id的文件夹名称，配置文件按打包之后的目录存放
* profile:produce 生产环境
* profile:test 测试环境


##用法
* 以父工程的形式引用到项目中

```xml
<parent>
	<groupId>cn.brent</groupId>
	<artifactId>brent-parent-webapp</artifactId>
	<version>1.0.0-SNAPSHOT</version>
</parent>
```

