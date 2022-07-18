Jenkinsfile (Declarative Pipeline)
pipeline {
    agent none 
    stages {
        stage('Build') { 
            steps {
		echo 'Hello, docker.image'
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
