pipeline {
    agent any
    
    stages {
	stage('checkout') {
	    steps {
		echo "Checckout Successful"
	    }
	}
        stage('Build') {
            steps {
                echo 'make clean build'
            }
        }
        stage('Test') {
            steps {
                echo 'make test'
            }
        }       
        stage('Deploy') {
            steps {
                echo 'make deploy'
            }
        }
}
