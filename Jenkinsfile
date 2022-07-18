Jenkinsfile (Declarative Pipeline)
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
        stage('Deploy') { 
            steps {
                echo 'this is deploy stage' 
            }
        }
    }
}
