pipeline {

    agent any
   // triggers {
     // cron('*/4 * * * *')

//    } 

    stages {
    //   stage ('GIT') {
     //       steps {
      //         echo "Getting Project from Git"; 
       //        git branch:"main", url : "https://github.com/smaiifakher/Devops-gomycode.git"; 
       //     }
        //}

       stage("Verification du version Maven") {
           steps {
                bat "mvn -version"
              
            }
        }
	
        	
    }
}