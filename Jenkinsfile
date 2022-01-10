pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Hello World"
                sh 'echo second step'
                sh 'echo another step'                
                sh '''
                echo 'Multilinem'
                echo 'Example'
                '''
                echo 'not using shell'
            }
        }
    }
}
