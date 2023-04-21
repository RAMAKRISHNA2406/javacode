pipeline { 
    agent any 
  stages {
    stage( 'clone the code ') {
      steps { 
          git branch: 'main' , credentialsId: 'githubcred' , url: 'https://github.com/RAMAKRISHNA2406/javacode'
        
          stage('build') { 
              steps { 
                  clean install
              }
          }
              
                       
          
      }
    }
  }
}
      
