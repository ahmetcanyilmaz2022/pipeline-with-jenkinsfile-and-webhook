pipeline {
    agent any
    stages {
        stage("Clean Up") {
            steps {
                deleteDir()
            }
        }
        stage("Clone Repo") {
            steps {
                sh "git clone https://github.com/ahmetcanyilmaz2022/pipeline-with-jenkinsfile-and-webhook.git"
            }
        }
        stage('Build') {
            steps {
                echo "deneme amacli"
                echo 'not using shell in the Jenkinsfile'
            }
        }
       
    }
}
