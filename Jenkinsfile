pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        svn(poll: true, url: 'svn://apphostsubversion2.orgdv.din.de/Docker/apps/vb.beuth.de/branches/test_branch/run', changelog: true)
      }
    }
  }
}