pipeline{
        agent any
        stages{
	    
            stage('Test App'){
                steps{
                    sh "./createTest.sh"
                }
            }
            stage('Build Image'){
                steps{
                    sh "./buid.sh"
		            }	
            }
            stage('Push Image'){
                steps{
                    sh "./push.sh"
		            }	
            }
	    
        }    
}
