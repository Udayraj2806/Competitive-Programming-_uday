pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Building.."
                bat  '''
                echo "doing build stuff.."
                '''
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
                bat '''
                    docker --version
                '''
                
            }
        }
        // stage('Deliver') {
        //     steps {
        //         echo 'Deliver....'
        //         bat '''
        //         echo "doing delivery stuff.."
        //         '''
        //     }
        // }
    }
}