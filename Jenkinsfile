pipeline {
    agent {
        node {
            label 'maven'
        }
    }

    stages {
        stage('Hello') {
            steps {
                git branch: 'main', url: 'https://github.com/DevPatel9110/tweet-trend-sourcecode.git'
            }
        }
    }
}