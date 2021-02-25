pipeline {
    agent { label 'ltecom'}
    stages {
        stage('scm') {
            steps {
                git 'https://github.com/komali306/spring-petclinic.git'
            }
        }
        stage('build') {
            steps {
                sh script: 'mvn clean package'
            }
        }
    }    
}


