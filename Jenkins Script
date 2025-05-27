pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World.....'
            }
        }
        stage('Build'){
            steps{
                echo 'Building the project....'
            }
        }
        stage('Deploy'){
            steps{
                echo 'Deploying the application....'
            }
        }
    }
    post{
        success{
            echo 'Pipeline completed successfully!'
        }
        failure{
            echo "Pipeline failed!"   
        }
    }
}
