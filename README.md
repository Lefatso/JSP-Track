#  ![jspicon](https://github.com/Lefatso/JSP-Track/assets/106061860/9095610a-398c-4ca8-b896-16a03300f4ed) ![netbeans icon](https://github.com/Lefatso/JSP-Track/assets/106061860/c7b078a5-a4a8-4026-a0ea-d6cf3b7112d8)![Apache tomcat Icon](https://github.com/Lefatso/JSP-Track/assets/106061860/8b0b7f88-8211-407d-a50e-2916f524fab0)
# **$${\color{orange} JSP- Hello World- Program}$$**

> This program is built using netbeans IDE with 	`JDK21`
 steps to build in (netbeans :
-  	`New project`
-  	Categories :	`Java with Gradle`
-   Project: 	`Web Application`
-   `Next`
- 	`Name the project	`
-   `Select your server (Apache Tomcat or TomEE)`
-   `Finish`
### By default the `index.html` is built in the Web Pages folder, since well we are building JSP program,you can delete `index.html`
and follow the following steps to create `index.jsp`\
  Righ click > New > JSP... > \
  ![Jsp-hello-world, creating jsp program](https://github.com/Lefatso/JSP-Track/assets/106061860/f274bd25-48c9-45ea-98e2-b9e9c6f56103) 
  \
  \
  name your file `index` then click `finish`.
  ![Jsp-hello-world, creating jsp program](https://github.com/Lefatso/JSP-Track/assets/106061860/623eb5db-ff03-425a-80e8-1fd5d90ed8a5)
  
  > [!NOTE]
  >why naming folder index? : This because by default if you run your projects in tomcat, the browser will
  >search for the file name index and run it, (this is preferred, but there are otherways to navigate to your folder in the brower search)

# Run> Results
This will be your output once you run your program
![Jsp-hello-world, netbeans results](https://github.com/Lefatso/JSP-Track/assets/106061860/9b5995ca-2328-4ebc-bfd8-064683f01ab0)


> [!NOTE]
> make sure that you have installed  and configured Apache tomcat server in netbeans


Go to the browser of your choice to and search `localhost:8080`
![Jsp-hello-world, localhost:8080 search](https://github.com/Lefatso/JSP-Track/assets/106061860/e33dee78-07f7-4c23-90c9-ef2116129d44)

This will direct you to this page : Select `Manager Apps`>
![Jsp-hello-world,Manager App](https://github.com/Lefatso/JSP-Track/assets/106061860/6cd4e772-a1f2-4945-acd3-c66c89c2e205)

Scroll and click in the name of your project that is uderlined to view the results:
![Jsp-hello-world, in tomcat](https://github.com/Lefatso/JSP-Track/assets/106061860/1b1a498c-211a-43db-86ae-bc3c91de6643)

# The results 
![Jsp-hello-world, in the browser](https://github.com/Lefatso/JSP-Track/assets/106061860/8bcfe838-e67a-4bff-a7c5-f9c06419f052)







## file tree stucture 
```
├───.gradle
│   ├───8.6
│   │   ├───checksums
│   │   ├───dependencies-accessors
│   │   ├───executionHistory
│   │   ├───fileChanges
│   │   ├───fileHashes
│   │   └───vcsMetadata
│   ├───buildOutputCleanup
│   ├───nb-cache
│   │   ├───Jsp-helloWorld-1268882486
│   │   │   └───org-netbeans-modules-profiler
│   │   └───trust
│   └───vcs-1
├───bin
│   └───main
│       └───Jsp
│           └───helloWorld
├───build
│   ├───exploded
│   │   └───Jsp-helloWorld.war
│   │       ├───META-INF
│   │       └───WEB-INF
│   ├───libs
│   └───tmp
│       ├───.cache
│       │   └───expanded
│       │       └───zip_cde35f471dab581134460fc9a50e2c59
│       │           ├───META-INF
│       │           │   └───maven
│       │           │       └───org.jacoco
│       │           │           └───org.jacoco.agent
│       │           └───org
│       │               └───jacoco
│       │                   └───agent
│       ├───assemble
│       ├───build
│       ├───buildDependents
│       ├───buildEnvironment
│       ├───buildNeeded
│       ├───check
│       ├───classes
│       ├───clean
│       ├───compileJava
│       ├───compileTestJava
│       ├───components
│       ├───dependencies
│       ├───dependencyInsight
│       ├───dependentComponents
│       ├───explodedWar
│       ├───help
│       ├───init
│       ├───jacocoTestCoverageVerification
│       ├───jacocoTestReport
│       ├───jar
│       ├───javadoc
│       ├───javaToolchains
│       ├───model
│       ├───outgoingVariants
│       ├───prepareKotlinBuildScriptModel
│       ├───processResources
│       ├───processTestResources
│       ├───projects
│       ├───properties
│       ├───resolvableConfigurations
│       ├───runSingle
│       ├───tasks
│       ├───test
│       ├───testClasses
│       ├───war
│       └───wrapper
├───gradle
│   └───wrapper
└───src
    └───main
        ├───java
        │   └───Jsp
        │       └───helloWorld
        └───webapp
            ├───META-INF
            └───WEB-INF
