node{
   stage('SCM Checkout'){
       git 'https://github.com/madhu1122/maven-web-app'
     }
     
     stage('Compile-Package'){
         sh 'mvn package'
     }
    
   stage('email Notifications'){
         emailext body: '''hii
          welcome to jenkins email''', subject: 'Jenkis job', to: 'vemulamadhu098@gmail.com'
    }

}
