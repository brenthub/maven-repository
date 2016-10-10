# maven-repository

私有Maven仓库

## 用法
* 仓库地址配置如下

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
