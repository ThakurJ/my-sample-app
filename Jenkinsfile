pipeline {
    agent {
        label "jenkinsagent"
    }

    environment {

    }

    tools {
      maven 'mvn_3_6_3'
      jdk 'jdk 1.8.0_192'
    }

    stages {
        stage('Example') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}