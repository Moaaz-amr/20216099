pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/Moaaz-amr/20216099/tree/master'
            }
        }
        stage('Run Bash Script') {
            steps {
                sh './script.sh'  
            }
        }
    }
}
