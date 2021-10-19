pipeline {
    agent any 
    stages {
        stage('Clone the repo') {
            steps {
                echo 'clone the repo'
                sh 'rm -fr Reveal'
                sh 'cd /var/www/html'
                sh 'git clone https://github.com/akashkumar0711/Reveal.git'
                sh 'cp html_files/index.html /var/www/html/index.html'
                
            }
        }
        stage('Clean the repo') {
            steps {
                echo 'clean the repo'
                cleanWs()
            }
        }
    }
}
