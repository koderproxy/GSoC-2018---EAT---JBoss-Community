GSoC submission 2018 
===================

### GSoC-2018---EAT---JBoss-Community

Link to the  work done on the project: [JBossModulesAT](https://github.com/koderproxy/JBossModulesAT)

Link to the workshop: [EAT_workshop ](https://www.dropbox.com/s/bebhyd1iz7cg1i2/EAT_WORKSHOP.odt?dl=0)

Link to project proposal: [EAT](https://summerofcode.withgoogle.com/projects/#5384917089779712)

----------

Introduction
-------------

Our project, which is included in the category of Software Testing, is related to EAT(EAP Additional Testsuite) with which we can test infinite software project versions. 


#### The advantages of EAT are :

1. Writing the tests once and testing against infinite number of Application Servers.
2. Having all the tests at one place.
3. Comparison of the servers based on the testsuite.
4. Guarding against regression.
5. Faster convergence among the servers.
6. Comparison of the servers based on tests of the past and the present.
7. Addition of tests with possible future features that are not at the moment available.
8. It makes possible to push a testcase of a fix regarding a specific component of the server, without the component version to have been updated at the server pom.
9. Ability to merge tests from remote testsuites.


#### This GSoC 2018 Project had three phases :

1. Going through the EAT workshop lab : [EAT_workshop ](https://www.dropbox.com/s/bebhyd1iz7cg1i2/EAT_WORKSHOP.odt?dl=0) .
2. Adding the latest release of Wildfly (while in 2nd Phase) in EAT.
3. Use the generalized AT structure to create an AT (Additional Testsuite) for a multi-versioned JBoss project (JBoss-modules).


GSoC 2018 RESULT / PRODUCTION
------------------------------

#### Phase 1

During the 1st phase I went through the workshop lab. 

Among the tasks was downloading and building the sources of different JBoss servers and JBoss server versions such as [Wildfly](https://github.com/wildfly/wildfly),[Wildfly 10.1.0](https://github.com/wildfly/wildfly/releases/tag/10.1.0.Final),[EAP 7.1.0.Beta server](https://developers.redhat.com/products/eap/download/) and testing them using [EAT](https://github.com/jboss-set/eap-additional-testsuite). 

Below, there is a url link which contains screenshots of the EAT runs for all the servers / server versions done during this phase :
[Phase-1 Screenshots](https://www.dropbox.com/sh/32zaykvtav3im3w/AAAcaovgOW8fOlE7Wtz7ZS1xa?dl=0)

Also, during this phase, I have added a new test subset for Wildfly server [Wildfly2 Screenshots](https://www.dropbox.com/sh/xyza30llr2se3pk/AABr2Qcxdcx6IlmZbXyA1xEha?dl=0) and I have tested different versions of the [JBoss-Threads](https://github.com/jbossas/jboss-threads) component using JBTAT - JBoss Threads Additional Testsuite ( [JBTAT screenshots]( https://www.dropbox.com/sh/dqffo0niy5x6esg/AAB0GMKmiL4XInXT-Z_dyawLa?dl=0) ).



#### Phase 2

During the 2nd phase I have added the latest release (at the time) of Wildfly server in EAT, creating a new test set, which was used with the EAT Travis CI build on Github.  Here is the PR that was merged : [EAT PR](https://github.com/jboss-set/eap-additional-testsuite/pull/41) and here is the successful [Travis CI build](https://travis-ci.org/jboss-set/eap-additional-testsuite/builds/405257910).

This work was tracked by the following Jira : [GSoC-2018 : Creation of a test subset snapshot for Wildfly 13.0.0.Final in EAT](https://issues.jboss.org/browse/WFLY-10560)



#### Phase 3

During the 3rd phase, I have applied the  Generalized AT Structures, that can be applied for any software program of any software language, in order to create an Additional Testsuite for the JBoss-Modules component called JBossModulesAT where we test different versions of JBoss-Modules of different branches such as 1.x, 1.8, 1.7, 1.6 .

Here is the url of the project I have created : [JBossModulesAT](https://github.com/koderproxy/JBossModulesAT) 
and the commits of this project :  [JBossModulesAT commits](https://github.com/koderproxy/JBossModulesAT/commits/master)

The documentation of this project can be found in the README.md file of the JBossModulesAT github repo : [JBossModulesAT Documentation](https://github.com/jboss-set/eap-additional-testsuite/blob/master/README.md) 







