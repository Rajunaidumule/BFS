pipeline {
  agent any
  
  stages {
  
stage('Deployment') {
  steps {
  bat 'mvn -U -V -e -B  clean deploy -DmuleDeploy'
  }
  }
  
  }
}
