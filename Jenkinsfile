pipeline {
	tools {
        maven 'Maven'
        jdk 'JDK8'
    }
	agent any
	stages {
		stage('--clean--') {
			ste[sps {
				bat "mvn clean"
			}
		}
		stage('--test--') {
			steps {
				bat "mvn test"
			}
		}
		stage('--package--') {
			steps {
				bat "mvn package"
			}
		}
}
