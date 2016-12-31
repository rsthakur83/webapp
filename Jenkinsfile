node {
   
   	stage 'Stage 1'
   		echo 'Hello Deploying Thakur App'
   	stage 'Checkout'
   		git url: 'https://github.com/rsthakur83/webapp.git'
      stage 'Execute'
         chmod +x 'myDeployment.sh'
      stage 'Deploy'
   		sh './myDeployment.sh'
  
}
