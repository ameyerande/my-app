
node {
   stage('SCM Checkout'){
    // Clone repo
	git 'https://github.com/ameyerande/my-app'//branch: 'master', 
	//credentialsId: 'github', 
	url: 'https://github.com/javahometech/myweb'
   
   }
   
   stage('Mvn Package'){
	   // Build using maven
	 sh 'mvn packege'
   }
}

