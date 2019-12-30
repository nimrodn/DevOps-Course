pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                /* `make check` returns non-zero on test failures,
                * using `true` to allow the Pipeline to continue nonetheless
                */
                sh 'make check || true' 
                sh 'echo Hello Zulu' 
            }
            }
            steps {
                sh 'echo Hello Zulu1'
            }
          }
        }
}
