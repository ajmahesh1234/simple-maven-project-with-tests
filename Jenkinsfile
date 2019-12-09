pipeline {
    agent any
    stages {
        stage('build Stage') {
            steps {
               withMaven(maven : 'Maven' ){
                bat 'mvn clean'
	       }
		
                
            }
        }
    }
}
