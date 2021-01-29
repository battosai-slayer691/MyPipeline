pipeline {
    agent any
    stages {
        stage("build") {
        
            steps {
                echo 'building the application'
            }
        }

       stage("test") {
            steps {
                echo 'testing the application'           
            }
        }

        stage("deploy") {
            steps {
                echo 'deploying the application'

            }
            stage('Email Notification'){
               mail bcc: '', body: 'Email settings worked', cc: '', from: '', replyTo: '', subject: 'Testing Conf', to: 'battosai864@gmail.com'
            }
        }
    }
}
