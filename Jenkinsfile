pipeline {
  agent any
  
  stages {
  
stage('Deployment') {
  steps {
  bat 'mvn -U -V -e -B -gs %M2SETTINGS% -DskipTests deploy -DmuleDeploy'
  }
  }
  
  }
}
