pipeline {
  agent any

  stages{
    stage('Hello'){
      steps {
        echo 'Hello'
      }
    }

    stage('Hello1'){

      when {
         branch 'fix-*'   
      }

      steps {
        echo 'Hello from fix file'
      }
    }
  }
}
