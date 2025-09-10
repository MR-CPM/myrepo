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

~
~
~
~
~
~
~
~
~
~
~
~
~
"Jenkinsfile" 30L, 550B                                                                            1,1           All
pipeline {
    agent any

    stages {
                stage('Checkout Code') {
    steps {
        git branch: 'main', url: 'https://github.com/MR-CPM/myrepo.git'
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

~
~
~
~
~
~
~
~
~
~
~
-- INSERT --                                                                                       5,7           All
