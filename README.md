mvn-repo
================

A lighweight maven repository alternative, hosted by github in order to use jar not (already) published on the maven central repository.


----

## pom.xml

This repository can be added as a remote maven repository, using the configuration:

```xml
<repository>
	<id>mvn-repo</id>
	<url>https://raw.githubusercontent.com/seralf/mvn-repo/master/repository</url>
	<releases>
		<enabled>true</enabled>
	</releases>
	<snapshots>
		<enabled>true</enabled>
	</snapshots>
</repository>
```



