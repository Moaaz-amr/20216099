pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/Moaaz-amr/20216099'
            }
        }
        stage('Run Bash Script') {
            steps {
                sh './script.sh'  
            }
        }
    }
}
