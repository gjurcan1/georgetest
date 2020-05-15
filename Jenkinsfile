pipeline {
    agent none
    stages {
        stage('Do Things') {
            parallel {
                stage('Make Container') {
                    agent {
                        label "jenkins-slave"
                    }
                    steps {
                        sleep 300
                    }

                }
                stage('Make Container1') {
                    agent {
                        label "jenkins-slave"
                    }
                    steps {
                        sleep 300
                    }

                }
                stage('Make Container2') {
                    agent {
                        label "jenkins-slave"
                    }
                    steps {
                        sleep 300
                    }

                }
            }
        }
    }
}