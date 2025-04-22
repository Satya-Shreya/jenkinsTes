pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "building pipeline"
                sh 'cat file.txt'
            }
        }

        stage('Done') {
            steps {
                echo "build done"
            }
        }
    }
}
