pipeline {
    agent any
    stages {
        stage('Deloy') {
            steps {
                timeout(time:1, unit:'MINUTES') {
                    sh '/var/lib/jenkins/scripts/fibonacci.sh 5'
                }
                timeout(time:1, unit:'MINUTES') {
                    sh '/var/lib/jenkins/scripts/fibonacci.sh 32'
                }
            }
        }
    }
}
