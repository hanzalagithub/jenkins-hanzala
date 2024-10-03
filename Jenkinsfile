pipeline {
    agent { 
        node {
            label 'docker-agent-python'
            }
      }
    triggers {
        pollSCM 'H/5 * * * *'
    }
    stages {
        stage('Build') {
            steps {
                echo "Building.."
                sh '''
                echo " Doing Building Stuff"
                '''
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
                sh '''
                echo "Testing Hahaha"
                '''
            }
        }
        stage('Deliver') {
            steps {
                echo 'Deliver....'
                sh '''
                echo "Pro hehe"
                '''
            }
        }
    }
}
