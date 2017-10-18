# PharmGKB Project Template

Template for starting new public PharmGKB projects.

1. Create repo on GitHub
    * Initialize with README
    * Add the MPL 2.0 license
2. Check out repo
3. Copy the following files from this repo to the new repo:
    * `.editorconfig`
    * `.gitattributes`
    * `.gitignore`
4. If this is a Java project that's going to use gradle, then also copy:
    * `build.gradle`
    * `pgkb-build.gradle`



## Gradle-based projects

All you should have to do is edit `build.gradle` and replace the `XXX` placeholders with the proper values and update the dependency

Public gradle-based projects are assumed to be published to Bintray.  The `pgkb-build.gradle` script plugin should automatically configure everything properly.


### IntelliJ IDEA

Don't commit IDEA config files for gradle-based projects.

After cloning the repo, use:

1. *File* > *Open Project from Existing Sources*
2. *Import project from existing model* (Gradle)
3. Select *Use auto-import*




## Badges

Code for badges we're using.  Replace the `XXX` placeholders.

```
[![Build Status](https://travis-ci.org/PharmGKB/pgkb-XXX.svg?branch=master)](https://travis-ci.org/PharmGKB/pgkb-XXX)
[![Coverage Status](https://coveralls.io/repos/github/PharmGKB/pgkb-XXX/badge.svg?branch=master)](https://coveralls.io/github/PharmGKB/pgkb-XXX?branch=master)
[![codecov.io](https://codecov.io/github/PharmGKB/pgkb-XXX/coverage.svg?branch=master)](https://codecov.io/github/PharmGKB/pgkb-XXX?branch=master)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.pharmgkb/pgkb-XXX/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.pharmgkb/pgkb-XXX)
[ ![Download](https://api.bintray.com/packages/pharmgkb/maven/pgkb-XXX/images/download.svg) ](https://bintray.com/pharmgkb/maven/pgkb-XXX/_latestVersion)
```

