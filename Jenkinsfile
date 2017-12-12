pipeline {
  agent {
    docker {
      image 'registry.din.de/din-wf/wfbuildenv:1.0'
      args '--add-host=wf9-ci-hudson:10.3.35.89 -v $JENKINS_HOME/.m2:/home/maven/.m2'
    }
    
  }
  stages {
    stage('build') {
      steps {
        sh 'hostname'
      }
    }
  }
}