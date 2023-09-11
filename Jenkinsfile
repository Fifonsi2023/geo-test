 pipeline{
    agent any 
    tools{
         maven 'opt/maven/bin/M2_HOME'
    }
 }
    stages{
    stage('maven clean'){
        steps{
        sh  'opt/maven/bin/mvn clean'
        }
    }
    }
    stage('maven install'){
        steps{
          sh  'opt/maven/bin/mvn install'
            
        }
    }
    stage('maven package'){
        steps{
         sh   'opt/maven/bin/mvn package'
        }
    }