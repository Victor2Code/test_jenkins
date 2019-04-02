pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                sh 'echo "Hello World"'
            }
        }
        stage('check'){
            steps{
                input 'How is the build result?'
            }
        }
        stage('release'){
            steps{
                sh 'echo "We can proceed to release now."'
            }
        }
    }
}
