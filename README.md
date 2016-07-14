#brent-parent

##工程说明
* 提供pom常用配置和常用jar包引用
* 此工程为pom类型，不能直接引用


##用法
* 以父工程的形式引用到项目中

```xml
<parent>
	<groupId>cn.brent</groupId>
	<artifactId>brent-parent</artifactId>
	<version>1.0.0-SNAPSHOT</version>
</parent>
```

##仓库引用
```xml
<repositories>
	<repository>
		<id>brent-snapshots</id>
		<name>brent repository</name>
		<url>https://raw.githubusercontent.com/brenthub/maven-repository/master/snapshots</url>
	</repository>
	<repository>
		<id>brent-releases</id>
		<name>brent repository</name>
		<url>https://raw.githubusercontent.com/brenthub/maven-repository/master/releases</url>
	</repository>
	<repository>
		<id>brent-public</id>
		<name>brent repository</name>
		<url>https://raw.githubusercontent.com/brenthub/maven-repository/master/public</url>
	</repository>
</repositories>
```
