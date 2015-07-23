## Maven setup for the EasyMock API with JUnit for PowerMock up to 1.4.5 ##
Add the following to your pom.xml if you're using JUnit 4.4 or above:

```
<repositories>
   <repository>
      <id>powermock-repo</id>
      <url>http://powermock.googlecode.com/svn/repo/</url>
   </repository>
</repositories>
<properties>
    <powermock.version>1.4.5</powermock.version>
</properties>
<dependencies>
   <dependency>
      <groupId>org.powermock.modules</groupId>
      <artifactId>powermock-module-junit4</artifactId>
      <version>${powermock.version}</version>
      <scope>test</scope>
   </dependency>
   <dependency>
      <groupId>org.powermock.api</groupId>
      <artifactId>powermock-api-easymock</artifactId>
      <version>${powermock.version}</version>
      <scope>test</scope>
   </dependency>  
</dependencies>
```

> Add the following to your pom.xml if you're using JUnit 4.0-4.3:

```
<repositories>
   <repository>
      <id>powermock-repo</id>
      <url>http://powermock.googlecode.com/svn/repo/</url>
   </repository>
</repositories>
<properties>
    <powermock.version>1.4.5</powermock.version>
</properties>
<dependencies>
   <dependency>
      <groupId>org.powermock.modules</groupId>
      <artifactId>powermock-module-junit4-legacy</artifactId>
      <version>${powermock.version}</version>
      <scope>test</scope>
   </dependency>
   <dependency>
      <groupId>org.powermock.api</groupId>
      <artifactId>powermock-api-easymock</artifactId>
      <version>${powermock.version}</version>
      <scope>test</scope>
   </dependency>  
</dependencies>
```

> Add the following to your pom.xml if you're using JUnit 3:

```
<repositories>
   <repository>
      <id>powermock-repo</id>
      <url>http://powermock.googlecode.com/svn/repo/</url>
   </repository>
</repositories>
<properties>
    <powermock.version>1.4.5</powermock.version>
</properties>
<dependencies>
   <dependency>
      <groupId>org.powermock.modules</groupId>
      <artifactId>powermock-module-junit3</artifactId>
      <version>${powermock.version}</version>
      <scope>test</scope>
   </dependency>
   <dependency>
      <groupId>org.powermock.api</groupId>
      <artifactId>powermock-api-easymock</artifactId>
      <version>${powermock.version}</version>
      <scope>test</scope>
   </dependency>  
</dependencies>
```