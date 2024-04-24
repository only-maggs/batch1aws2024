pipeline {
  agent any
  stages {
    stage('working with loops') {
      steps {
        script {
            for (i=1;i<=10 ;i++) {
              println "my i value is ${i}"
            }
            list1=[10,20,30,40]
            for (element in list1) {
              println "my element is ${element}"
            }
        }
      }
    }
  }
}
