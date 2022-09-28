pipeline {
    agent any 
    environment {
        my_var = "123"
    }
    
    stages {
        stage("Stage 1") {
            steps {
                echo 'Hello World'
                echo "The status is ${currentBuild.currentResult}"
            }
        }
        stage("Stage 2") {
            steps {
                echo "We are at stage 2!"
            }
        }
        stage("Stage 3") {
            steps {
                echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
            }
        }
    }
}
