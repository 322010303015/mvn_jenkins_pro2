pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat '''
			mvn package
			java -jar target/java-project2-1.0-SNAPSHOT.jar
		'''
            }
        }
    }
}
