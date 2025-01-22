pipeline {
  agent any 
  environment {
    JAVA_PATH = "/opt/bin/java11"
  }
  parameters {
    choice choices: ['dev', 'sit', 'pt', 'prod'], description: 'Select environment', name: 'ENV'
    string defaultValue: '0.0.0', description: 'Provide the version', name: 'VERSION', trim: true
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
          println "my selected environment is ${params.ENV}, version to be deployed is ${params.VERSION}"
        }
      }
    }
  }
}
