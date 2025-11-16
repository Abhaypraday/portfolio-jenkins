pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'main',
                    url: 'url: 'https://github.com/Abhaypraday/portfolio-jenkins.git'
'
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying Website..."
                bat 'xcopy /E /I /Y * C:\\jenkins-deploy\\portfolio\\'
            }
        }
    }
}
