pipeline {
  agent any
  tools {
    maven "maven3"
  }
  stages {
    stage("build ") {
      steps {     
        sh 'mvn clean install'
      }
    }
    stage("stage3") {
      steps {     
        sh 'echo stage 3 completed'
      }
    }
    stage("stage4 ") {
      steps {     
        sh 'echo stage 4 completed'
      }
    }
    stage("stage5 ") {
      steps {     
        sh 'echo stage 5 completed '
      }
    }
    stage("stage6 ") {
      steps {     
        sh 'echo stage 6 completed '
      }
    }
  }
}
