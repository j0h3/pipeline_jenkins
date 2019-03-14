pipeline {
    agent {
        docker { image 'img-python' }
    }
    stages {
        stage('Launch') {
            steps {
                sh 'python /srv/test/test.py'
            }
            step {
                sh 'echo OK'
            }
        }
    }
}