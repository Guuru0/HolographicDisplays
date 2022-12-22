# Launcher password: uni1010

Make sure to leave a star if this repository helped you!

Holographic Displays
===================

Development Builds: https://ci.codemc.io/job/filoghost/job/HolographicDisplays

## Maven
```xml
<repository>
    <id>codemc-repo</id>
    <url>https://repo.codemc.io/repository/maven-public/</url>
</repository>
```

```xml
<dependency>
    <groupId>me.filoghost.holographicdisplays</groupId>
    <artifactId>holographicdisplays-api</artifactId>
    <version>3.0.0</version>
    <scope>provided</scope>
</dependency>
```

## Gradle
```groovy
maven {
  url "https://repo.codemc.io/repository/maven-public/"
}
```

```groovy
compileOnly 'me.filoghost.holographicdisplays:holographicdisplays-api:3.0.0'
```

## License
Holographic Displays is free software/open source, and is distributed under the [GPL 3.0 License](https://opensource.org/licenses/GPL-3.0). It contains third-party code, see the included THIRD-PARTY.txt file for the license information on third-party code.