pipeline {
    agent { label 'jenkinsnode' }

    stages {

        stage('Build') {
            steps {
                echo "Building Simple HTML App"
            }
        }

        stage('Deploy') {
            steps {
                sh '''
                sudo cp -r * /usr/share/nginx/html/
                '''
            }
        }
    }
}
