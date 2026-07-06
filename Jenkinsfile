pipeline {
    agent any

    stages {
        stage('git clone') {
            steps {
               git branch: 'main', url: 'https://github.com/Diddi-123/spring-petclinic.git'
            }
        }
         stage('genrate a build') {
            steps {
            sh 'mvn package'
            }
        }
    }
}
