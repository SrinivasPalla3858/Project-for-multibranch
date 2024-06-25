pipeline {

  agent any

  stages {

    stage('build') {

      steps {

        sh '''

          ls -ltr
	  free -h
	  ps
	  git --version
	  git branch
        '''

      }

    }

  }

}

