pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building'
                cmd 'mvn compile -DRELEASE_TAG=1.1.3"
            }
        }
    }
}
