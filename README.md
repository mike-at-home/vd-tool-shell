# vd-tool

This downloads the required Android source files and builds a self-contained ("fat") jar of vd-tool.

## Usage
`./gradlew build` to build (result in `build/distributions`)

`vd-tool.sh` may be used to run the utility, or run the jar manually.

## Updating
At some point, build.gradle may need to be updated to:
* add an external dependency
* update an external dependency
* adjust one of the copy steps to pull in more internal files
* download more internal folders in the form of tar.gz
* (hopefully not) preprocess downloaded source files to remove or edit dependencies

## Notes
`src` purposefully is empty
