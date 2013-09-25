xgbi-tmp-maven-repository
=========================

Temporary maven repository (before using the Sonatype OSS service), **you shouldn't use it**.

If you **really** want to use it :

## Releases

```xml
<repositories>
  <repository>
    <id>xgbi-releases</id>
    <url>https://raw.github.com/xgbi/xgbi-tmp-mvn-repository/master/releases</url>
  </repository>
</repositories>
```

## Snapshots  

```xml
<repositories>
  <repository>
    <id>xgbi-snapshots</id>
    <url>https://raw.github.com/xgbi/xgbi-tmp-mvn-repository/master/snapshots</url>
  </repository>
</repositories>
```
