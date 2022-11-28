pipeline {
    agent any
    stages {
        stage(‘Build’) {
            steps {
                echo ‘Build-Hello Jenkins’
            }
        }
    }
    post {
        always {
            echo ‘I will always say Hello again!’
        }
    }
}
    
