pipeline {
    agent any
    stages {
        stage('--test-deploy--') {
            steps {
            	sh "ssh -T -i /home/jenkins/Project.pem ubuntu@ec2-3-11-81-76.eu-west-2.compute.amazonaws.com ./selenium-get.sh"
            }
        }
    }
}
