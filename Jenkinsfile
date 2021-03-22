node {
    stage('Build') {
        checkout scm
        def app = docker.image('golang:alpine')
        app.pull()
        app.inside {
            sh 'go build'
        }
    }
}