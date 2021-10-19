pipeline {
    agent any 
    stages {
        stage('Clone the repo') {
            steps {
                echo 'clone the repo'
                sh 'rm -fr Reveal'
                sh 'git clone https://github.com/akashkumar0711/Reveal.git' 
                sh 'ls /var/lib/jenkins/workspace'
                sh 'ls /var/lib/jenkins/jobs'
            }
        }
       
    }
}
