pipeline {
    agent { 
        node {
            label 'docker-agent-python'
            }
      }
       triggers {
        pollSCM '*/5 * * * *'
    }
    stages {
        stage('Build') {
            steps {
                echo "Building.."
                sh '''
                echo "doing build stuff for me.."
                '''
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
                sh '''
                echo "doing test stuff for me.."
                '''
            }
        }
        stage('Deliver') {
            steps {
                echo "Deliver...."
                sh '''
                echo "doing delivery stuff for me.."
                '''
            }
        }
    }
}
