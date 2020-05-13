pipeline {
     agent any
     stages {
		stage('Lint HTML') {
              steps {
                  sh 'tidy -q -e webapp/src/main/webapp/index.jsp'
              }
         }
     }
}
