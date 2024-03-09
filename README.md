Nemesis Platform BOM
===========
[![GitHub Release](https://img.shields.io/github/release/nemesis-software/nemesis-bom.svg?maxAge=3600)](https://github.com/nemesis-software/nemesis-bom/releases/latest)

The parent BOM for the Nemesis Platform.

= RELEASE

```
mvn release:prepare -B -DdryRun=false -Dtag=2.3.17 -Dnemesis.version=2.3.17.RELEASE -DdevelopmentVersion=2.3.18.BUILD-SNAPSHOT -DreleaseVersion=2.3.17.RELEASE

mvn release:perform

```
