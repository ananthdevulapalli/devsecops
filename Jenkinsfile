pipeline {
    agent any

    environment {
        registry = "ananthdevulapalli/web"
        registryCredential = 'docker'
    }

    stages {
        stage('Checkout') {
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'd79075a4-8fa8-4803-bfbc-fe76bbbfa56c', url: 'https://github.com/ananthdevulapalli/demo-java.git']]])
            }
        }
        
    
    }
}
