pipeline {
    agent any
    // We split the work into 3 stages:
    stages {
        // 1. Checkout the files from Git
        stage ('Prep') {
            steps {
                checkout scm
            }
        }
    }
}
