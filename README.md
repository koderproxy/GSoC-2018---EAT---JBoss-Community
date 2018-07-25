GSoC submission 2018 
===================

### GSoC-2018---EAT---JBoss-Community

Link to the  work done on the project: [JBossModulesAT](https://github.com/koderproxy/JBossModulesAT)

Link to the workshop: [EAT_workshop ](https://www.dropbox.com/s/bebhyd1iz7cg1i2/EAT_WORKSHOP.odt?dl=0)

Link to project proposal: [EAT](https://summerofcode.withgoogle.com/projects/#5384917089779712)

----------

Introduction
-------------

Our project come in category of Testing which is   EAT(EAP additional Testsuite)   by which we can Test infinite software project versions .The best thing of EAT is creating the test once and testing with any version of the tested software . We can firstly applied with jBoss Servers  and after that for similar structures .it has ability to merge test from remote. Project  has three phase :

     > Taking  idea by going through EAT workshop
     > Create  different test sets at the server layer using the existent tests of EAT
     > Use the generalized AT structure to create an AT for multi-versioned  any java project .


Phasly breakdown of work done
-------------------

####  Community bonding period 
 During this one month, I spent time reading and understanding EAT from Workshop. 


#### Phase 1


in these phase i was followed workshop . Download and build the source of different version such as [Wildfly](https://github.com/wildfly/wildfly),[Wildfly 10.1.0](https://github.com/wildfly/wildfly/releases/tag/10.1.0.Final),[EAP 7.1.0.Beta server](https://developers.redhat.com/products/eap/download/) and finally [EAT](https://github.com/jboss-set/eap-additional-testsuite).
 
i have tested all different server , here is the url link for screenshot of all different servers.

[Phase-1 Screenshots](https://www.dropbox.com/sh/32zaykvtav3im3w/AAAcaovgOW8fOlE7Wtz7ZS1xa?dl=0)


#### Phase 2

in these phase we was continue workshop and move further use EAT inside an IDE such as Eclipse and others also creating a testcase in EAT. here is the screenhot of these >> [Wildfly2](https://www.dropbox.com/sh/xyza30llr2se3pk/AABr2Qcxdcx6IlmZbXyA1xEha?dl=0). After that we go through the  JBTAT(JBoss Threads Additional Testsuite).Download the source [jboss-thread](https://github.com/jbossas/jboss-threads) and try to build with different version here is the screenshots for these [JBTAT]( https://www.dropbox.com/sh/dqffo0niy5x6esg/AAB0GMKmiL4XInXT-Z_dyawLa?dl=0) after that i was doing some update in EAT project here is all commit >>[commits](https://github.com/jboss-set/eap-additional-testsuite/pull/41/commits/5e3b8217e07c6f33686e9a598c5f02e745e44674).


#### Phase 3
these is the last phase of GSOC 2018 and in these phase i was faced a project named JBossModulesAT(JBossModulesAT is an implementation of the AT Structures for the JBoss-Modules testsuite) we have to test different version in these project such as 1.x,1.7,1.6 and others here is the url for my project [JBossModulesAT](https://github.com/koderproxy/JBossModulesAT) and these is the commit i have done all in these project [commits](https://github.com/koderproxy/JBossModulesAT/commits/master)







