pipeline {
    agent {
        label "jenkinsagent"
    }



    stages {
        stage('Example') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}