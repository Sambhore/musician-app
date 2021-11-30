pipeline {
    agent any

    stages {
        stage('file path') {
            steps {
               echo pwd
               path= pwd
              echo $path
            }
        }
        
        stage('-----test----') {
            steps {
               echo 'mvn test'
            }
        }
        
        stage('-----package----') {
            steps {
               echo 'mvn package'
            }
        }
    }
}
