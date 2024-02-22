pipeline {
    agent { label 'slave1' }
    stages {
        stage('Clone Step') {
            steps {
                sh 'rm -rf hello-world-war'
                sh 'git clone https://github.com/surendrakorivi/hello-world-war.git'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn package'
            }
        }
    }
}
