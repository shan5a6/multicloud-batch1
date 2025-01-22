pipeline {
  agent any 
  environment {
    JAVA_PATH = "/opt/bin/java11"
  }
  stages{
    stage('working with variables') {
      steps {
        script {
          batchno = 1
          topic = "jenkins scriptingg"
          println "my batch no is ${batchno},my current topic is ${topic}"
          println "my workspace is ${WORKSPACE}"
          println "my java path is ${env.JAVA_PATH}"
          
        }
      }
    }
  }
}
