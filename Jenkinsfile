pipeline {
  agent any
  stages {
      stage("Pre-Build") {
        steps {
          sh 'flutter doctor'
        }
      }
      stage("Build") {
        steps {
          sh 'flutter build apk --split-per-abi --debug'
        }
      }
    }
}
