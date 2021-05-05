@Library('shared-library@master') _
 
pipeline {
    agent any
    stages {
        stage('Git Checkout') {
            steps {
            checkout(
                branch: "master",
                url: "https://github.com/samayaramesh/module"
            )
            }
    }
    }
}
