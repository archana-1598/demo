pipeline {
     agent any 
	 stages {
	     stage('Compile') {
		     steps {
			       echo "Compiled sucessfully !";
				   }
			}
		 stage('JUnit') {
		    steps {
			       echo "Junit passed successfully!";
				   }
			}
			stage('Qulaity gate') {
		    steps {
			       echo "quality gate passed successfully!";
				   }
			}
			stage('Deploy') {
		    steps {
			       echo "Pass";
				   }
			}
   }
}
