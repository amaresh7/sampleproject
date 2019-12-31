pipeline{
 agent{
       node{
        label 'MAVEN1' 
       } 
     }
   stages{
     stage('build'){
       steps{
          echo "This is a build"
       }
     }
     stage('test'){
       steps{
          echo "This is a test"
        }
      }
     stage('deploy'){
       steps{
          echo "This is a deploy"
     }
   }
 }
}
