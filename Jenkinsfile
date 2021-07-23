pipeline
{
  agent {label 'tomcat'}

  stages{
    stage('build'){
      sh 
      ''''
        mvn install
      ''''
    }
    stage('deploy'){
      sh
      ''''
        cp target/*.war ../../
      ''''
    }
  
  }

}
