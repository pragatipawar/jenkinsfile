pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh "rm -r xyz"
                sh "mkdir xyz"
                sh " ls -l"
                sh "pwd"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
        stage('MySql installation') {
            steps { 
                sh "sudo apt-get update"
                //sh "sudo apt-get install -y mysql-server"
                //sh "sudo ufw allow mysql"
                sh "export DEBIAN_FRONTEND=noninteractive"
                sh "aptitude -y install mysql-server > /dev/null 2>&1"
            }
        }    
    }
}
