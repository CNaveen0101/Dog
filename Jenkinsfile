pipeline{
    agent any

    tools {
      maven 'Maven'
    }

    stages {
        stage('Checkout') {
            steps {
                echo "Code checkout stage passed"
            }
        }

        stage('Build') {
            steps {
               sh 'mvn clean package'
            }
                
            
        }
    }
}
