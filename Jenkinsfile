pipeline {

        agent {
		
		      label {
			  
			  
			         label "slave-2"
					 customWorkspace "/mnt/abs/"
			  
			  
			  }
		
		
		}
		
		stages {
		
		
		               stage ("sequence-stge") {
					   
					   
					          steps {
							  
							  
							          sleep 10
							  
							  
							  }
					   
					   
					   }
					   
					   stage ("parallel-sequence") {
					   
					   
					           parallel {
							   
							   
							           stage ("prllel-1") {
									   
									   
									         steps {
											 
											 
											         sleep 10
											 
											 }
									   
									   
									   }
									   stage ("prllel-2") {
									   
									   
									         steps {
											 
											 
											         sleep 10
											 
											 }
									   
									   
									   }
							   
							   
							   
							   }
					   
					   
					   
					   }
		
		
		
		}


}
