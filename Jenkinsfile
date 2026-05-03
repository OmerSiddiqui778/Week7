pipeline{
    agent any 

    stages {
        stage('Build'){
            steps {
                echo "Build Stage"
            }
        }
        stage('Unit and Integration Tests'){
            steps{
                echo "Using Selenium to run tests.... "
            }
        }
        stage('Code Analysis'){
            steps{
                echo "analysing code using SonarQube..."
            }   
        }
        stage('Security Scan'){
            steps{
                echo "Performing a security scan using OWASP Dependency Checker..."
            }
        }
        stage('Deploy to Staging'){
            steps{
                echo "Deploying the application to AWS EC2..."
            }
        }
        stage('Integration Tests on Staging'){
            steps{
                echo "Running integration tests on staging environment..."
            }
        }
        stage('Deploy to Production'){
            steps{
                echo "Deploying application to AWS EC2 production server..."
            }

        }
    }
}