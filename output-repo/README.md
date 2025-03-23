# Superscary Maven Repository

This is a Maven repository hosted on GitHub Pages that contains various tools and libraries.

## Repository URL

```
https://superscary.github.io/maven-repo
```

## Available Artifacts

### Nightjar
- Group ID: `net.superscary.tools`
- Artifact ID: `nightjar`
- Version: `1.0.0`
- Packaging: `jar`

## Usage

To use this repository in your Maven project, add the following repository configuration to your `pom.xml`:

```xml
<repositories>
  <repository>
    <id>superscary-github</id>
    <url>https://superscary.github.io/maven-repo</url>
  </repository>
</repositories>
```

Then you can add the dependency:

```xml
<dependency>
    <groupId>net.superscary.tools</groupId>
    <artifactId>nightjar</artifactId>
    <version>1.0.0</version>
</dependency>
```

## Repository Structure

This repository follows the standard Maven repository layout:

```
net/
└── superscary/
    └── tools/
        └── nightjar/
            ├── maven-metadata.xml
            └── 1.0.0/
                ├── nightjar-1.0.0.jar
                ├── nightjar-1.0.0.jar.md5
                ├── nightjar-1.0.0.jar.sha1
                ├── nightjar-1.0.0.pom
                ├── nightjar-1.0.0.pom.md5
                └── nightjar-1.0.0.pom.sha1
```

## License

[Add your license information here] 