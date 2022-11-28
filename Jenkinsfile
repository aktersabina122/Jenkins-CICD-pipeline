pipeline {
    agent any
    stages {
        stage(‘Build’) {
            steps {
                echo ‘Hello Jenkins’
            }
        }
     
     agent any
     stages {
        stage(‘Test’) {
            steps {
                echo ‘Testing stage’
            }
        }
      
      agent any
      stages {
        stage(‘Deploy’) {
            steps {
                echo ‘Deploy stage’
            }
        }
    }
}
