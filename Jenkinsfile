pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout the code from your repository
                git 'https://github.com/adarshadshetty09/jenkins.git'
            }
        }

        stage('Run Banner Script') {
            steps {
                script {
                    // Run the banner.sh script
                    sh './banner.sh'
                }
            }
        }
    }
}
