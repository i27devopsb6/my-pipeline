pipeline {
    agent any 
    stages {
        stage ('Build') {
            steps {
                echo "********** Building the application *******************"
            }
        }
        stage ('Sonar') {
            steps {
                echo "******************* Scanning the application ****************"
            }
        }
        stage ('Docker') {
            steps {
                echo "***************Building the docker image *************************"
            }
        }
    }
}
