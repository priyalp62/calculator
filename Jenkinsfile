pipeline {
     agent any
     stages {
          stage("Compile") {
               steps {
                    sh "bash ./gradlew compileJava"
               }
          }
          stage("Unit test") {
               steps {
                    sh "bash ./gradlew test"
               }
          }
     }
}
