pipeline {

agent any 

stages{

	stage('SCM'){

		steps	{
	
			echo " git Pull my code for java code"
			git 'https://github.com/vimallinuxworld13/simple-java-maven-app.git/'
	
	}
}
	
	stage('Deploy'){

		steps	{
		
			 echo " Deploying  my code"

	}
}

		stage('Test') {
  			
			steps {
				 echo " Test my code"
		}
	}


}

}
