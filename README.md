maven-repo
==========

maven repository with my all artifacts

Add repository
--------------

```
<repository>
    <id>dralagen-maven-repo</id>
    <url>https://raw.github.com/dralagen/maven-repo/master/</url>
    <snapshots>
        <enabled>true</enabled> <!-- or false if you use stable version -->
        <updatePolicy>always</updatePolicy>  <!-- optional -->
    </snapshots>
</repository>
```

