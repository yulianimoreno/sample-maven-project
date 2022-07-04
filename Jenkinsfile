pipeline {
    agent any
    tools {
        maven 'Maven_3.5.2' 
    }
    stages {
      stage('maven install') {
        steps {
          
           bat 'mvn clean install'
          
        }
      }

  }
}
