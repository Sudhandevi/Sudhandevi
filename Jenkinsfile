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
              stage ('Build develop'){
          when{
            branch "dev"          
          }
            steps{
              echo "Building Develop"               
                          
            }   
            }
       }
  }
