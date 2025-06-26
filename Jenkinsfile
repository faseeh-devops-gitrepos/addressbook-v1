pipeline {
    agent any

    stages {
        stage('compile') {
            steps {
                echo 'compile the code'
            }
        }
        stage('code review') {
            steps {
                echo 'review the code'
            }
        }
        stage('unittest') {
            steps {
                echo 'test the code'
            }
        }
        stage('coverageanalysis') {
            steps {
                echo 'static code coverage'
            }
        }
        stage('package') {
            steps {
                echo 'package the code '
            }
        }
      stage('publish to jfrog') {
            steps {
                echo 'publish the artifacts to jfrog'
            }
        }  
    }
