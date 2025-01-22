def myfn(a,b){
  sum = a + b 
  println "sum of a and b is ${sum}"
}
pipeline {
  agent any 
  stages{
    stage('working with function') {
      steps {
        script {
          myfn(100,200)
          myfn(1000,2000)
          myfn(500,600)
        }
      }
    }
  }
}
