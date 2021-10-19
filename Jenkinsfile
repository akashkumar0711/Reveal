pipeline {
    agent any 
    stages {
        stage('Clone the repo') {
            steps {
                echo 'clone the repo'
                sh 'rm -fr Reveal'
                sh 'git clone https://github.com/akashkumar0711/Reveal.git'
                sh 'cd /var/lib/jenkins/workspace/'
                sh 'cp /var/lib/jenkins/workspace/Reveal/* /var/www/html'
                
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
