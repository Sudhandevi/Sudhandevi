pipeline{
    agent any
    stages{
        stage ('Build Master'){
          when{
            branch "master"          
          }
            steps{
              echo "Building Masster"               
                          
            }   
            }
              stage ('Build Develop'){
          when{
            branch "develop"          
          }
            steps{
              echo "Building Develop"               
                          
            }   
            }
       }
  }
