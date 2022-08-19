
pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
		echo 'docker.image'
            }
        }
        stage('Test') { 
            steps {
                echo 'Hello, JDK'
                sh 'java -version' 
            }
        }
        stage('soanr analysis') { 
            steps {
		    echo 'sonar-scanner'
            }
        }
    }
}
