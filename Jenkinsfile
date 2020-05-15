pipeline {
    agent none

    stages {
        stage('Build') {
            agent { label 'jenkins-slave'}
            steps {
                echo 'Building..'
            }
        }
    }
}