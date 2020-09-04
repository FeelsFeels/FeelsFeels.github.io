pipeline {
    agent any
    stages {
        stage("build") {
            steps {
                echo 'building the app...'
            }
        }
        stage("test") {
            steps {
                echo 'testing the app...'
                cat index.html
            }
        }
        stage("deploy") {
            steps {
                echo 'deployeee the app...'
            }
        }
    }
}