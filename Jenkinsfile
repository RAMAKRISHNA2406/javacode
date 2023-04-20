pipeline { 
    agent any 
  stages {
    stage( 'clone the code ') {
      steps { 
          git branch: 'main' , credentialsid: 'githubcred' , url: 'https://github.com/RAMAKRISHNA2406/javacode'
      }
    }
  }
}
      
