---
title: Apache Groovy
category: lang
tags: apache java-runtime
iconSlug: apachegroovy
permalink: /apache-groovy
alternate_urls:
-   /groovy
-   /groovy-lang
versionCommand: groovy --version
releasePolicyLink: https://groovy.apache.org/versioning.html
changelogTemplate: https://groovy-lang.org/changelogs/changelog-__LATEST__.html
releaseColumn: true
releaseDateColumn: true
activeSupportColumn: true
eolColumn: Bug and Security Fixes

auto:
-   maven: org.apache.groovy/groovy
-   maven: org.codehaus.groovy/groovy

releases:
-   releaseCycle: "4.0"
    releaseDate: 2022-01-25
    eol: false
    support: true
    latest: "4.0.15"
    latestReleaseDate: 2023-09-11

-   releaseCycle: "3.0"
    releaseDate: 2020-02-10
    support: false
    eol: false
    latest: "3.0.19"
    latestReleaseDate: 2023-08-22

-   releaseCycle: "2.5"
    releaseDate: 2018-05-30
    support: false
    eol: false
    latest: "2.5.23"
    latestReleaseDate: 2023-08-22

-   releaseCycle: "2.4"
    releaseDate: 2015-01-21
    support: false
    eol: true
    latest: "2.4.21"
    latestReleaseDate: 2020-12-03

---

> [Apache Groovy](https://www.groovy-lang.org/) is a powerful, optionally typed and dynamic
> language, with static-typing and static compilation capabilities, for the Java platform
> aimed at improving developer productivity thanks to a concise, familiar and easy to learn
> syntax. It integrates smoothly with any Java program, and immediately delivers to your
> application powerful features, including scripting capabilities, Domain-Specific Language
> authoring, runtime and compile-time meta-programming and functional programming.

Apache Groovy does not have a fixed release policy. Its support policy states that each new major
version makes the previous major version go into maintenance. Versions that are into maintenance
are maintained for one or two bugfix releases and then discontinued, unless there are strong
requests to have certain things fixed for users that can absolutely not upgrade. Groovy 2.5 and
Groovy 3.0 are still supported because they are still in widespread use.

In Groovy 4.0, the groupId of the maven coordinates for Groovy have changed from
`org.codehaus.groovy` to `org.apache.groovy`.

Groovy have [the following JVM requirements](https://groovy.apache.org/download.html):

| Groovy | JVM Required (non-indy) | JVM Required (indy) |
|--------|:------------------------|---------------------|
| 4.0    | N/A                     | 8+                  |
| 3.0    | 8+                      | 8+                  |
| 2.5    | 7+                      | 7+                  |
| 2.4    | 6+                      | 7+                  |
