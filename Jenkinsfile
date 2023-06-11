pipeline {
    agent {
        node{
            label 'mavenagent'
        }
    }

    stages {
        stage('clone') {
            steps {
                git branch: 'main', url: 'https://github.com/veejee2331/webapplication.git'
            }
        }
    }
}
