
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
		    withSonarQubeEnv ('sonarqube-8.9'){
                echo 'this is deploy stage' 
		    }
            }
        }
    }
}
