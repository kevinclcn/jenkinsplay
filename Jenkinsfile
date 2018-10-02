pipeline {
    agent any
    
    stages {
        stage('Example') {
            steps {
                echo "${params.SERVICES}"
                echo "${env.BRANCH_NAME}"
            }
        }
    }

}