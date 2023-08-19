node {
    docker.image('node:16-buster-slim').inside('-p 3000:3000') {
        stage('Build') {
                sh 'ls /var/jenkins_home/workspace/submission-cicd-pipeline-dianyehezkiel/'
                sh 'npm install'

        }

        stage('Test') { 

                sh './jenkins/scripts/test.sh'

        }

    }

}