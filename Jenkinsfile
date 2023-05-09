pipeline {
    agent any

    stages {
        stage('Deploy') {
            steps {
                sh '''
                sudo -S apt update -y
                cd Nodejs-using-Jenkins-to-AWS-EC2
                npm restart
                npm install
                npm start 
            '''
            }
        }
    }
}