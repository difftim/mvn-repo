# mvn-repo

## Deploy
```sh
mvn clean deploy
mvn clean deploy -Dmaven.test.skip=true
```

```xml
<distributionManagement>
    <repository>
        <id>github</id>
        <name>GitHub OWNER Apache Maven Packages</name>
        <url>https://maven.pkg.github.com/difftim/mvn-repo</url>
    </repository>
</distributionManagement>
```

setting.xml
```xml
<servers>
    <server>
        <id>github</id>
        <username>maxsuren</username>
        <password>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</password>
    </server>
</servers>
```
