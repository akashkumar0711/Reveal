pipeline {
    agent any 
    stages {
        stage('Clone the repo') {
            steps {
                echo 'clone the repo'
                sh 'sudo su'
                sh 'password for akash : ttn'
                sh 'rm -rf Reveal'
                sh 'git clone https://github.com/akashkumar0711/Reveal.git' 
                sh 'pwd'
                sh 'cd /var/lib/jenkins/workspace/pipeline-demo/Reveal'
                sh 'chmod 777 index.html'
                
                sh 'sudo cp -rf /var/lib/jenkins/workspace/pipeline-demo/Reveal/index.html /var/www/html'
                sh 'pwd'
        
            }
        }
       
    }
}
