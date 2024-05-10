pipeline{
  agent any
    environment {
        DOCKER_IMAGE = 'nodejs-app'
}
  stages {
        stage('Checkout') {
            steps {
                git url: 'TWOJ_ADRES_DO_REPO', branch: 'main'
            }
        }
