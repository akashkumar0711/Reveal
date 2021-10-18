pipeline {
    agent any 
    stages {
        stage('Clone the repo') {
            steps {
                echo 'clone the repo'
                sh 'cd /var/www/html'
                sh 'git clone https://github.com/akashkumar0711/webapp1.git'
            }
        }
    }
}
