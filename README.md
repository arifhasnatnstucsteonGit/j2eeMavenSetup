j2eeMavenSetup
==============

স্প্রিং ম্যাভেন ও জেডিবিসি নিয়েে

With this only have to setup odbc14 maven dependacy with localhost 

mvn install:install-file -DgroupId=com.oracle -DartifactId=ojdbc14 -Dversion=10.2.0.1.0 -Dpackaging=jar -Dfile=ojdbc14.jar -DgeneratePom=true
