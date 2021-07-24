pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "hello World"'
            }
        }
        stage('BuildMore') {
            steps {
                sh '''
                  echo "multiline step"
                  ls -lah
                  '''
            }
        }
    }
}
