pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git 'https://github.com/MR-CPM/myrepo.git'
            }
        }

        stage('Build') {
            steps {
                echo "No build needed, just HTML!"
            }
        }

        stage('Test') {
            steps {
                sh 'test -f index.html'
            }
        }

        stage('Deploy') {
            steps {
                sh 'sudo cp index.html /var/www/html/index.html'
            }
        }
    }
}

