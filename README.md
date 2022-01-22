## Packages
Packages/Artifact Repository - List of Artifacts [here](https://gitlab.com/shibme/pkg/-/packages)

#### How to add maven repository to your project
Use the following repository in your `pom.xml`
```xml
<repositories>
    <repository>
        <id>shibme-gitlab-maven</id>
        <name>ShibMe GitLab Maven Packages</name>
        <url>https://gitlab.com/api/v4/projects/26425676/packages/maven</url>
    </repository>
</repositories>
```

#### Go packages
Available Go packages can be found [here](https://pkg.shib.me)