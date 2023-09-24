pipeline {

    stages {
        stage('Build') {
            steps {
                sh 'python3 ops.py'
            }
        }
        stage('Testing file') {
            steps {
                echo "python3 -m pytest"
            }
        }
        stage('Deliver') {
            steps {
                echo "Deliver...."
            }
        } 
    }
}