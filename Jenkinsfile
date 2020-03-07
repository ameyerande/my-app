
node {
   stage('SCM Checkout'){
    // Clone repo
	
	git 'https://github.com/ameyerande/my-app'//branch: 'master', 
	//credentialsId: 'github', 
	url: 'https://github.com/javahometech/myweb'
   
   }
   
   stage('Mvn Package'){
	   // Build using maven
	 def mavenHome = tool type: 'Maven'
	 sh '/usr/share/apache-maven/bin/mvn package'
   }
}

