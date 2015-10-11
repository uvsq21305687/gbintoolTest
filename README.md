$ gradle tasks
$ gradle build
:compileJava UP-TO-DATE
:compileGroovy
Download https://repo1.maven.org/maven2/org/codehaus/groovy/groovy-all/2.4.5/groovy-all-2.4.5.jar
:processResources UP-TO-DATE
:classes
:jar
:assemble
:compileTestJava UP-TO-DATE
:compileTestGroovy UP-TO-DATE
:processTestResources UP-TO-DATE
:testClasses UP-TO-DATE
:test UP-TO-DATE
:check UP-TO-DATE
:build

BUILD SUCCESSFUL

Total time: 1 mins 10.772 secs
$ ls build/libs
gradletuto.jar
$ java -cp $GROOVY_HOME/lib/groovy-2.4.5.jar:build/libs/gradletuto.jar fr.uvsq.doosa.gradletuto.Main
Hello
