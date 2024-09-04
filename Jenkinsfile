@Library("my-shared-library") _
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                helloWorld()
            }
        }
        stage('Build') {
            steps {
                mavenBuild()
            }
        }
    }
}
