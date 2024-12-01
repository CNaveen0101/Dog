pipeline{
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo "Code checkout stage passed"
            }
        }

        stage('Build') {
            steps {
                mvn clean package
            }
                
            
        }
    }
}
