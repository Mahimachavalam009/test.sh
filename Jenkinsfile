pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                // Clone the repository
                git 'https://github.com/Mahimachavalam009/test.sh'
            }
        }
        stage('Build') {
            steps {
                // Marking a build stage for demonstration, no actual build here
                echo "Nothing to build in this Hello World example"
            }
        }
        stage('Test') {
            steps {
                // Run the hello_world.sh script
                sh './hello_world.sh'
            }
        }
    }
}
