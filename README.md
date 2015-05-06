# sqlite-osgi

Provides a Gradle build file that uses the [bnd-platform](https://github.com/stempler/bnd-platform) plugin to create an OSGi bundle containing the [SQLite JDBC driver from Xerial](https://bitbucket.org/xerial/sqlite-jdbc). The bundle is designed to be easily integrated with the [HALE](https://github.com/igd-geo/hale) platform.

Prior to launching the build, edit the *build.gradle* file to make sure *eclipseHome* variable points to the path of your Eclipse local installation directory.
