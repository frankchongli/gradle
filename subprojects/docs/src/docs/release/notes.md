## New and noteworthy

Here are the new features introduced in this Gradle release.

<!--
IMPORTANT: if this is a patch release, ensure that a prominent link is included in the foreword to all releases of the same minor stream.
Add-->

### Default Zinc compiler upgraded from 0.3.7 to 0.3.13
This will take advantage of performance optimizations in the latest [Zinc](https://github.com/typesafehub/zinc) releases. 

<!--
### Example new and noteworthy
-->

## Promoted features

Promoted features are features that were incubating in previous versions of Gradle but are now supported and subject to backwards compatibility.
See the User guide section on the “[Feature Lifecycle](userguide/feature_lifecycle.html)” for more information.

The following are the features that have been promoted in this Gradle release.

<!--
### Example promoted
-->

## Fixed issues

## Deprecations

Features that have become superseded or irrelevant due to the natural evolution of Gradle become *deprecated*, and scheduled to be removed
in the next major Gradle version (Gradle 4.0). See the User guide section on the “[Feature Lifecycle](userguide/feature_lifecycle.html)” for more information.

The following are the newly deprecated items in this Gradle release. If you have concerns about a deprecation, please raise it via the [Gradle Forums](https://discuss.gradle.org).

<!--
### Example deprecation
-->

## Potential breaking changes

<!--
### Example breaking change
-->

## External contributions

We would like to thank the following community members for making contributions to this release of Gradle.

- [Ion Alberdi](https://github.com/yetanotherion) - Fix lazy evaluation of parent/grand-parent pom's properties ([gradle/gradle#1192](https://github.com/gradle/gradle/pull/1192))
- [Guillaume Delente](https://github.com/GuillaumeDelente) - Fix typo in user guide ([gradle/gradle#1562](https://github.com/gradle/gradle/pull/1562))
- [Guillaume Le Floch](https://github.com/glefloch) - Support of compileOnly scope in buildInit plugin ([gradle/gradle#1536](https://github.com/gradle/gradle/pull/1536))
- [Eitan Adler](https://github.com/grimreaper) - Remove some some duplicated words from documentation ([gradle/gradle#1513](https://github.com/gradle/gradle/pull/1513))
- [Eitan Adler](https://github.com/grimreaper) - Remove extraneous letter in documentation ([gradle/gradle#1459](https://github.com/gradle/gradle/pull/1459))
- [Pierre Noel](https://github.com/petersg83) - Add missing comma in `FileReferenceFactory.toString()` ([gradle/gradle#1440](https://github.com/gradle/gradle/pull/1440))
- [Hugo Bijmans](https://github.com/HugooB) - Fixed some typos and spelling in the JavaPlugin user guide ([gradle/gradle#1514](https://github.com/gradle/gradle/pull/1514))
- [Andy Wilkinson](https://github.com/wilkinsona) - Copy resolution listeners when a configuration is copied ([gradle/gradle#1603](https://github.com/gradle/gradle/pull/1603))
- [Tim Hunt](https://github.com/mitnuh) - Allow the use of single quote characters in Javadoc task options header and footer ([gradle/gradle#1288](https://github.com/gradle/gradle/pull/1288))
- [Jenn Strater](https://github.com/jlstrater) - Add groovy-application project init type ([gradle/gradle#1480](https://github.com/gradle/gradle/pull/1480))
- [Jacob Ilsoe](https://github.com/jacobilsoe) - Update Zinc to 0.3.13 ([gradle/gradle#1463](https://github.com/gradle/gradle/issues/1463))

We love getting contributions from the Gradle community. For information on contributing, please see [gradle.org/contribute](https://gradle.org/contribute).

## Known issues

Known issues are problems that were discovered post release that are directly related to changes made in this release.
