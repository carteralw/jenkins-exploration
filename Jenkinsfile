node { 
    withEnv(['DISABLE_AUTH=true',
             'DB_ENGINE=sqlite']) {
        stage('Build') {
            echo "Database engine is ${DB_ENGINE}"
            echo "DISABLE_AUTH is ${DISABLE_AUTH}"
            sh 'printenv'
        }
        stage('Specific Vars'){
            echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
        }
    }
}