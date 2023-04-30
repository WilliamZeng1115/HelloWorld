pipeline {
    triggers {
        pollSCM '* * * * *'
    }
    stages {
        stage('Build') {
            steps {
                echo "Pulling dependencies and building.."
                sh '''
                '''
            }
        }
        stage('Test') {
            steps {
                echo "Running tests.."
                sh '''
                python3 hello.py
                '''
            }
        }
        stage('Deliver') {
            steps {
                echo 'Delivering files to destinations....'
                sh '''
                echo "delivery stuff"
                '''
            }
        }
    }
}
