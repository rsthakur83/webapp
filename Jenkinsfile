node {
   
   	stage 'Stage 1'
   		echo 'Hello Deploying Thakur App'
   	stage 'Checkout'
   		git url: 'https://github.com/rsthakur83/webapp.git'
      stage 'Deploy'
         chmod +x 'myDeployment.sh'
   		sh './myDeployment.sh'
  
}
