pipeline {
  agent any
  stages {
    stage('working with file condition') {
      steps {
        script {
          File file =  new File("/tmp/testdata.txt")
          println file.readLines()
          for(line in file.readLines()){
            println "your line is ${line}" 
          } 
        }
      }
    }
  }
}
