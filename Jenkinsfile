pipeline{
  agent any
  stages{
    stage('clone'){
      steps{
          git branch: 'master',
          credentialsId:'8d5ecfcf-4597-400b-9999-82e207957ac9',
          url:'git@github.com:Anandbabuvc/simple-web-app.git'
      }
   }
    stage('sonarscan'){
	  steps{
	      echo "clone the repo"
      }
   }
   stage('unit Test'){
	  steps{
	      echo "clone the repo"
      }
   }
   stage('build war'){
	  steps{
	      echo "clone the repo"
      }
   }
   stage('upload war'){
	  steps{
	      echo "clone the repo"
      }
   }
   stage('deploy war'){
	  steps{
	      echo "clone the repo"
      }
   }
   stage('send email'){
	  steps{
	      echo "clone the repo"
      }
   }
  
 }
}
