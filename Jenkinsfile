pipeline {
  agent any 
  stages{
    stage('working with fileoperations') {
      steps {
        script {
          File myfilecontent = new File("/tmp/mydata.txt")
          println "${myfilecontent.text}"
          println myfilecontent.readLines()
          for (line in myfilecontent.readLines()) {
            println "my line is ${line}"
          }
        }
      }
    }
  }
}
