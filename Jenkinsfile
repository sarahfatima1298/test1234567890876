pipeline {
   agent any
   stages {
       stage('Build') {
        steps {
            snDevOpsStep()
        }
       }
       stage('Test') {
        steps {
            snDevOpsStep()
        }
       }
       stage('Deploy') {
        steps {
            snDevOpsStep()
            snDevOpsChange()
        }
       }
   }
}
