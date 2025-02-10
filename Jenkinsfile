pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout the code from your repository
                git 'https://your-repository-url.git'
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
