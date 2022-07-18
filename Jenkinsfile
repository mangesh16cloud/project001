Jenkinsfile (Declarative Pipeline)
pipeline {
    agent none 
    stages {
        stage('Build') {
	    agent { docker 'maven:3.8.1-adoptopenjdk-11' } 
            steps {
                sh 'mvn -B clean verify'
		echo 'Hello, docker.image'
            }
        }
        stage('Test') {
	    agent { docker 'openjdk:8-jre' } 
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
