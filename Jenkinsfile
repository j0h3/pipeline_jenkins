pipeline {
    agent {
        docker { image 'appli-python' }
    }
    stages {
        stage('Launch') {
            steps {
                sh 'python test.py'
            }
        }
    }
}