pipeline {
    agent any

    tools {
        maven 'mymaven'   // Must match the Maven installation name in Jenkins Global Tool Configuration
    }

    stages {
        stage('Clone Code') {
            steps {
                git url: 'https://github.com/Sonal0409/GITHUBJENKINSDEMO.git'
            }
        }

        stage('Compile Code') {
            steps {
                sh 'mvn compile'
            }
        }
    }
}
