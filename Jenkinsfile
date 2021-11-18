pipeline {

    agent {
        node {
            label 'master'
        }
    }

    stages {

        stage(' Unit Testing') {
            steps {
                sh """
                echo "Running Unit Tests"
                echo "Ciao"
                echo "Riciao"
                echo "Riciao"
                echo "Ciao"
                echo "Riciao"
                echo "Riciao"
                 echo "Riciao"
                echo "Riciao"
                echo "Riciao"
                echo "Riciao"
                 echo "Riciao"
                echo "Riciao"
                echo "Ciao2"
                echo "Ciao3"
                echo "Ciao4"
                echo "Ciao5"
                
                """
            }
        }

        stage('Code Analysis') {
            steps {
                sh """
                echo "Running Code Analysis"
                """
            }
        }

        stage('Build Deploy Code') {
            when {
                branch 'develop'
            }
            steps {
                sh """
                echo "Building Artifact"
                """

                sh """
                echo "Deploying Code"
                """
            }
        }

    }   

}
