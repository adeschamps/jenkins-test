pipeline {
    agent any
    stages {
        stage('build') {
            agent any
            steps {
                cargo build
                cargo test
            }
        }
    }
}
