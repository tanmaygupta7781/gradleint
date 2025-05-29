pipeline{
  agent any
  tools{
    maven 'Maven'
    gradle 'gradle'
    JDK 'jdk'
  }
  stages{
    stage('build'){
      steps{
        sh 'gradle build'
      }
    }
    stage('gradle run'){
      steps{
        sh 'gradle run'
      }
    }
    stage('display'){
      steps{
        sh 'gradle Display'
      }
    }
  }
}
      
  
