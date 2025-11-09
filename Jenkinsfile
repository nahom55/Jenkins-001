pipeline {
    agent any
    
    triggers {
        pollSCM '* * * * *'
    }

    stages {
        stage('Build') {
            steps {
                echo 'build'
                sh '''
                echo ' building staff '
                '''
            }
        }
        
        stage('Test') {
            steps {
                echo 'test'
                sh '''
                echo " testing staff "
                '''
            }
        }
        
        stage('Stage') {
            steps {
                echo 'stage'
                sh '''
                echo ' staging staff '
                '''
            }
        }
    }
}
