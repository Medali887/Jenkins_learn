pipeline {
    agent any
    options {
        // Timeout counter starts AFTER agent is allocated
        timeout(time: 1, unit: 'SECONDS')
    }
    stages {
        stage('build') {
            steps {
                echo 'Building the App...'
            }
        }

      stage('test') {
            steps {
                echo 'Testing the App...'
            }
        }

      stage('deploy') {
            steps {
                echo 'Deploying the App...'
            }
        }
    }
}
