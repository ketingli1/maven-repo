# Discrible
my personal maven repository.

# config
git clone git@github.com:ketingli1/maven-repo.git

`cd repository`  
`pwd`  
and get path

set pom.xml add content 
```xml
<distributionManagement>
    <repository>
      <id>hengyunabc-mvn-repo</id>
      <url>file:/Users/ketl/learn/project/maven-repo/repository/</url>
    </repository>
</distributionManagement>
```

now everything is ok!!!
