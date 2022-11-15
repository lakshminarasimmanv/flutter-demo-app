pipeline {
    agent any
    stages {
        stage("Pre-Build") {
          steps {
            sh 'flutter doctor'
          }
        }
        stage("Build") {
          flutter build apk --split-per-abi --debug
        }
        stage("Test") {

        }
        stage("Release") {

        }
    }
    post {

    }
}
