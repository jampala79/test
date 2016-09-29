node {
   
   	stage 'Stage 1'
   		echo 'Hello there, Demo Pipeline'
   	stage 'Checkout'
   		git url: 'https://github.com/jampala79/test'
   	stage 'Build'
   		sh './myBuild.sh'
	stage 'Change Request'
		sh './Change_Request.sh'
   	stage 'Deploy'
   		sh './myDeployment.sh'
	stage 'Run Tests'
		sh './Run_test.sh'
  
}
