pipeline {
    agent any

    stages {
        stage('file path') {
            steps {
               sh 'pwd'
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
