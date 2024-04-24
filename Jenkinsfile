pipeline {
    agent any
    stages {
        stage ('Building') {
            steps { 
			mvn clean deploy -DskipTests
                bat 'mvn clean deploy -DmuleDeploy' 
            }            
        }

    }
}