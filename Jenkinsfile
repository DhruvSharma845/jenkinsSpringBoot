pipeline {
    agent {
	docker { image 'openjdk:8-jdk-alpine' }
    }
    stages {
        stage('Build') {
            steps {
		sh 'java -version'
            }
        }
    }
}
