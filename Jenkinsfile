pipeline {
    agent any
    stages {
        stage('clone') {
            steps {
                git 'https://github.com/spring-petclinic/spring-framework-petclinic.git'
            }
        }
        stage(‘Build’) {
            steps {
                sh '''
                ./mvnw jetty:run-war
                
                '''
            }
        }
    }
}
