pipeline {
  agent any
  stages {
    stage('1') {
      steps {
        svn(poll: true, changelog: true, url: 'https://10.10.20.28/svn/GMAS/MichaelF/trunk/libraries/mmc_app')
      }
    }
  }
}