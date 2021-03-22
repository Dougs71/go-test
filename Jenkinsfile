node {
    stage('Build') {
        docker.image('golang:alpine').inside {
            sh 'go version'
        }
    }
}