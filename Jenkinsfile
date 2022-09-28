pipeline {
    agent any 
    environment {
	my_var = "123"
	}
    stage("Stage 1") {
        echo 'Hello World'
	echo "The status is ${currentBuild.currentResult}"
	// sh 'echo this is shell'
        }
    stage("Stage 2") {
        echo "We are at stage 2!"
    }
    stage("Stage 3") {
        echo $my_var
    }
}
