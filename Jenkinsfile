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
                    git clone https://github.com/Udayraj2806/Competitive-Programming-_uday.git
                '''
                 bat '''
                    git status
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