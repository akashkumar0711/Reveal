pipeline {
    agent any 
    stages {
        stage('Clone the repo') {
            steps {
                echo 'clone the repo'
                sh 'rm -rf Reveal'
                sh 'git clone https://github.com/akashkumar0711/Reveal.git' 
                sh 'pwd'
            }
        }
       
    }
}
