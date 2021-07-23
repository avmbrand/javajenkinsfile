pipeline
{
  agent {label 'tomcat'}

  stages{
    stage('build'){
      steps{
      sh '''
        mvn install
      '''
      
      }
      
    }
    stage('deploy'){
      steps{
        sh '''
        cp target/*.war ../../
      '''
      }
      }
  
  }

}
