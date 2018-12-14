node {
    stage('Test') {
        try {
            sh 'make check'
        }
        finally {
            junit 'D:\TestResults\*.xml'
        }
    }
}