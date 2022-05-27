pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git 'https://github.com/ppisaravana/jenkinsdemo.git'
                bat "./mybatch.bat"
            }
        }
        stage('Hello1') {
            steps {
                git 'https://github.com/ppisaravana/jenkinsdemo.git'
                bat "./mybatchclone.bat"
            }
        }
    }
}
