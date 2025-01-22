pipeline {
  agent any 
  stages{
    stage('working with loops') {
      steps {
        script {
          for (sub in ["aws","azure","devops","azure devops"]) {
            println "I learned subjects such as ${sub}"
          }
          for (i=1;i<=5;i++) {
            println "My i value is ${i}"
          }
          j = 10
          while(j <= 20 ) {
            println "my j value is ${j}"
            j = j + 1
          }
        }
      }
    }
  }
}
