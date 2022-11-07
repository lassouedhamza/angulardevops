pipeline {


    agent any
    stages{
        stage('Checkout GIT'){
         steps {
             echo 'Pulling ...';
              git branch: 'main',
              url : 'https://github.com/lassouedhamza/angulardevops.git'
         } 

        }


        

      
        stage('Building image docker-compose') {
          steps {

              sh "docker-compose up -d"
          }
        }

         
        	


	 

    }
}