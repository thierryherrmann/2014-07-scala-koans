scala-koans
===========

This is a copy of scala-koans from http://scalakoans.webfactional.com as of 2014-07-05 slightly updated to work with scalatest 2.2.0 and scala 2.11+

License: [Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License](http://creativecommons.org/licenses/by-nc-sa/3.0/)


To quickly play with the koans in an Eclipse environment:

- download/install ScalaIDE from http://scala-ide.org/ (successfully tested with 3.0.4 that comes with scala 2.11)
- Install the ScalaTest plugin: Help -> Install New Software -> Select Update Site: Scala IDE - http://download.scala-ide.org/sdk/helium/e38/scala211/stable/site
- right click on a Koan -> Run as -> ScalaTest File : no test should succeed
- replace the '__' with your solutions : re-execute : tests should start to succeed 

The pom.xml excludes the scala library that is a depedencency of scala test since already comes with ScalaIDE (e.g. scala 2.11 comes with ScalaIDE 3.0.4)
to avoid the 'More than one Scala library...' error (make sure you read  http://scala-ide.org/docs/user/faq.html to avoid any weird behavior with ScalaIDE)
