pipeline {
    node {}
    agent any
    options {

    }
    stages {
        stage("Pre-Build") {
          flutter doctor
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
