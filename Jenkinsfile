pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh 'make check || true' 
                sh 'echo Hello Zulu' 
            }
            }
            steps {
                sh 'echo Hello Zulu1'
            }
          }
}
