# Java Binary Decision Diagram

JDD is a decision diagram library written in pure java. It supports [Binary Decision Diagrams][bdd] (BDD) and [Zero-suppressed Decision Diagram][zdd] (Z-BDD or just ZDD).

There seems to be some ongoing development of the library at [1] (currently versioned with build number 107). 

This is a fork from [2] that includes an SBT (Simple Build Tool) build file (which provides also a ask for publishing via oss.sonatype.org). The source is versioned with build number 104. 

In order to include this library as a git dependency of a project declared in an SBT build environment and to compile it using an up-to-date Scala version, the subfolder JavaBDD has been removed. 

###References:
[1] https://bitbucket.org/vahidi/jdd/wiki/Home
[2] https://github.com/ckaestne/JavaBDD_repackaged
