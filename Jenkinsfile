pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'master', url: 'https://github.com/nadanehad/CloudTask2_20216109'
            }
        }
        stage('Execute Script') {
            steps {
                sh './script.sh'
            }
        }
    }
}
