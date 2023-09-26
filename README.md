vd-tool

This downloads the required Android source files and builds vd-tool.

At some point, build.gradle may need to be updated to:
* add an external dependency
* update an external dependency
* add more downloading/adjusted copying for internal dependencies
* (hopefully not) preprocess the downloaded source files


`src` purposefully is empty

`./gradlew copyFiles`
`./gradlew shadowJar`
