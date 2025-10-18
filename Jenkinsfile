pipeline {
    agent any

    stages {
        stage('JobA') {
            steps {
                echo 'Hello from JobA!'
                echo 'JobA completed successfully.'
            }
        }

        stage('JobB') {
            steps {
                echo 'Hello from JobB!'
                echo 'JobB is running after JobA.'
            }
        }
    }
}
