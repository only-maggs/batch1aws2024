pipeline {
    agent any
    enviornment {
        JAVA_HOME = "/usr/bin/java"
    }
    parameters {
      choice choices: ['dev', 'sit', 'pt', 'prod'], name: 'ENV'
   }
    stages {
      stage("welcome note") {
        steps {
          script {
            println "Welcome to jenkins pipeline tutorial"
            println "my workspace is ${WORKSPACE}"
            println "my build no is ${BUILD_NUMBER}"
            println "my env variable is ${env.JAVA_HOMES}

            println "my env value is ${params.ENV}"
              
          }
        }
      }
    }
}
