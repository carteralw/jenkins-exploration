def username = 'Jenkins'

pipeline {    
    agent any

    stages {
        stage("Build") {
            steps {
                echo "Hello Mr. ${username}"
            }
        }
        stage("Test") {
            steps {
                echo "Testing.."
            }
        }
        stage("Deploy") {
            steps {
                echo "Deploying...."
            }
        }
    }
}