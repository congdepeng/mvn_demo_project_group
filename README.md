mvn_application5
================









/Library/Java/JavaVirtualMachines/jdk1.7.0_45.jdk/Contents/Home/bin/java -Dmaven.home=/Users/depeng/apps/apache-maven-3.1.1 -Dclassworlds.conf=/Users/depeng/apps/apache-maven-3.1.1/bin/m2.conf -Didea.launcher.port=7532 "-Didea.launcher.bin.path=/Applications/IntelliJ IDEA 13.app/bin" -Dfile.encoding=UTF-8 -classpath "/Users/depeng/apps/apache-maven-3.1.1/boot/plexus-classworlds-2.5.1.jar:/Applications/IntelliJ IDEA 13.app/lib/idea_rt.jar" com.intellij.rt.execution.application.AppMain org.codehaus.classworlds.Launcher package
[INFO] Scanning for projects...
[INFO] ------------------------------------------------------------------------
[INFO] Reactor Build Order:
[INFO] 
[INFO] appC
[INFO] libA
[INFO] libB
[INFO]                                                                         
[INFO] ------------------------------------------------------------------------
[INFO] Building appC 1.0
[INFO] ------------------------------------------------------------------------
[INFO]                                                                         
[INFO] ------------------------------------------------------------------------
[INFO] Building libA 1.0
[INFO] ------------------------------------------------------------------------
[INFO] 
[INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ libA ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] Copying 0 resource
[INFO] 
[INFO] --- maven-compiler-plugin:2.5.1:compile (default-compile) @ libA ---
[WARNING] File encoding has not been set, using platform encoding UTF-8, i.e. build is platform dependent!
[INFO] Compiling 1 source file to /Users/depeng/github/depeng/mvn_application5/libA/target/classes
[INFO] 
[INFO] --- maven-resources-plugin:2.6:testResources (default-testResources) @ libA ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] skip non existing resourceDirectory /Users/depeng/github/depeng/mvn_application5/libA/src/test/resources
[INFO] 
[INFO] --- maven-compiler-plugin:2.5.1:testCompile (default-testCompile) @ libA ---
[INFO] Nothing to compile - all classes are up to date
[INFO] 
[INFO] --- maven-surefire-plugin:2.12.4:test (default-test) @ libA ---
[INFO] No tests to run.
[INFO] 
[INFO] --- maven-jar-plugin:2.4:jar (default-jar) @ libA ---
[INFO] Building jar: /Users/depeng/github/depeng/mvn_application5/libA/target/libA-1.0.jar
[INFO]                                                                         
[INFO] ------------------------------------------------------------------------
[INFO] Building libB 1.0
[INFO] ------------------------------------------------------------------------
[INFO] 
[INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ libB ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] Copying 0 resource
[INFO] 
[INFO] --- maven-compiler-plugin:2.5.1:compile (default-compile) @ libB ---
[WARNING] File encoding has not been set, using platform encoding UTF-8, i.e. build is platform dependent!
[INFO] Compiling 1 source file to /Users/depeng/github/depeng/mvn_application5/libB/target/classes
[INFO] 
[INFO] --- maven-resources-plugin:2.6:testResources (default-testResources) @ libB ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] skip non existing resourceDirectory /Users/depeng/github/depeng/mvn_application5/libB/src/test/resources
[INFO] 
[INFO] --- maven-compiler-plugin:2.5.1:testCompile (default-testCompile) @ libB ---
[INFO] Nothing to compile - all classes are up to date
[INFO] 
[INFO] --- maven-surefire-plugin:2.12.4:test (default-test) @ libB ---
[INFO] No tests to run.
[INFO] 
[INFO] --- maven-jar-plugin:2.4:jar (default-jar) @ libB ---
[INFO] Building jar: /Users/depeng/github/depeng/mvn_application5/libB/target/libB-1.0.jar
[INFO] ------------------------------------------------------------------------
[INFO] Reactor Summary:
[INFO] 
[INFO] appC .............................................. SUCCESS [0.002s]
[INFO] libA .............................................. SUCCESS [1.946s]
[INFO] libB .............................................. SUCCESS [0.072s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 2.148s
[INFO] Finished at: Thu Jan 02 23:28:10 SGT 2014
[INFO] Final Memory: 11M/161M
[INFO] ------------------------------------------------------------------------

Process finished with exit code 0
