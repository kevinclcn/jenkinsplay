pipeline {
    agent any
    
    parameters {
        string(name: 'Greeting', defaultValue: 'Hello', description: 'How should I greet the world?')
    }
    stages {
        stage('Example') {
            steps {
                script {
                    hosts = readYaml file: 'config/host.yml'
                }
                
                echo "${hosts}"
                echo "${params.Greeting} World!"
            }
        }
    }

}