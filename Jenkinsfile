node('worker_node') {
    
    stage('source') {
        
     git 'https://github.com/ankurmishra727/DeploymentWithJenkinsFile.git'




	}



      stage('deploy') {
          
         sh 'python test.py'
	 sh 'python test1.py'


	  }




    }
