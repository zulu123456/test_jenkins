pipeline {
    agent any

    environment {
        // Az autentikációs adatokat egy környezeti változóba töltjük
        CREDENTIALS_ID = '58fffba8-ea8d-4c25-b9bb-09ed2b8f2dcf'
    }

    stages {
        stage('Checkout') {
            steps {
                script {
                   
                        sh '''
                        echo 'hi'
                        '''
                }
            }
        }
    }
    post {
        always {
            cleanWs()
        }
    }
}
