pipeline {

	agent any
stages{

	stage('SCM'){

		steps	{
	
			echo " git Pull my code for java code "
			git 'https://github.com/vimallinuxworld13/simple-java-maven-app.git/'
	
	}
}
	
	stage('build'){

		steps	{
		
			sh 'mvn clean package'

	}
}

		stage('Test') {
  			
			steps {
				 echo " Test my code"
		}
	}


}

}
