@@ -1,5 +1,5 @@
 # gradletuto
Un court tutoriel Gradle
Un court tutoriel Gradle.
 
 ## Première tâche
 ```
 @@ -14,6 +14,9 @@ BUILD SUCCESSFUL
 Total time: 0.991 secs
 ```
 
### Voir aussi
* [Task](https://docs.gradle.org/current/dsl/org.gradle.api.Task.html)

 ## Dépendances entre tâches
 ```
 $ gradle world
 @@ -55,6 +58,12 @@ $ java -cp $GROOVY_HOME/lib/groovy-2.4.5.jar:build/libs/gradletuto.jar fr.uvsq.d
 Hello
 ```
 
### Voir aussi
* Plugin [Groovy](https://docs.gradle.org/current/userguide/groovy_plugin.html)
* Plugin [Java](https://docs.gradle.org/current/userguide/java_plugin.html)
* [repositories](https://docs.gradle.org/current/dsl/org.gradle.api.Project.html#org.gradle.api.Project:repositories%28groovy.lang.Closure%29)
* [dependencies](https://docs.gradle.org/current/dsl/org.gradle.api.Project.html#org.gradle.api.Project:dependencies%28groovy.lang.Closure%29)

 ## Lancer l'application
 ```
 $ gradle run
 @@ -69,3 +78,6 @@ BUILD SUCCESSFUL
 
 Total time: 1.663 secs
 ```

### Voir aussi
* Plugin [application](https://docs.gradle.org/current/userguide/application_plugin.html)
