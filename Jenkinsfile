node {  
    stage('Build') { 
        bat 'make'  
    }
    stage('Test') { 
        bat 'make check'
        junit 'reports/**/*.xml' 
    }
    stage('Deploy') { 
        bat 'make publish'
    }
}
