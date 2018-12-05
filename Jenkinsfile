node {  
    stage('Build') { 
        bat 'make'
 	archiveArtifacts artifacts: '**/target/*.jar', fingerprint: true
    }
}
