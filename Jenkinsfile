pipeline {
    agent {
        docker { image 'node:7-alpine' }
    }
    stages {
        stage('Test') {
                steps {
                checkout('https://github.com/mathias-dietrich/spinnaker.git')
                
            }
        }
    }
}
