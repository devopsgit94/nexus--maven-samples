pipeline{

      agent {
                docker {
                image 'maven'
                args '-u root -v /root/.m2:/root/.m2'
                }
            }
        
        stages{

              stage('deploy'){
                  steps{
			  script{
			    sh "pwd"
		    	    sh "mvn clean deploy"
		  
                 	}
               	 }  
              }	
		
            }	       	     	         
}
