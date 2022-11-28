pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Build-Hello World'
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
    
