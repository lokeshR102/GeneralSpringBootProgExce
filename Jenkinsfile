   pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git branch: 'development', url: 'https://github.com/lokeshR102/GeneralSpringBootProgExce.git'
                sh 'mvn clean package'
            }
        }
    }
}
