pipeline{
    agent any
    stages{
        stage('Checkout'){
            steps{
                echo 'Checking out the code...'
            }
        }
        stage('Build'){
            steps{
                echo 'Building the application...'
            }
        }
        stage('Test'){
            steps{
                echo 'Running tests...'
            }
        }
        stage('Deploy'){
            steps{
                echo 'Deploying the application...'
            }
        }
    }
    post{
        success{
            echo 'Pipeline executed successfully.'
        }
        failure{
            echo 'Pipeline execution failed.'
        }
        always{
            echo 'Pipeline execution completed.'
        }
    }
}