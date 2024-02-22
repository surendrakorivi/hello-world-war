pipeline {
    agent any
    stages {
        stage('Clone Step') {
            steps {
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
