pipipeline {
agent { label 'master' }

tools{
 jdk 'Java'
 maven 'Maven'
}

stages{
  stage('Git checkout'){
    steps{
        git branch: 'main',
        url: 'https://github.com/chinni4321/helloworld.git'
    }
  }
  stage('Maven Build'){
    steps{
      sh 'mvn clean install'
    }
  }
  
 } 
}
