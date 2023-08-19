node {
    docker.image('node:18-buster').inside('-p 3000:3000') {
        stage('Build') {

                sh 'npm install'

        }

        stage('Test') { 

                sh './jenkins/scripts/test.sh'

        }

    }

}