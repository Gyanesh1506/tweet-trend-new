pipeline{
    agent{
       node{
        label "MAVEN"
       }	
    }
    stages{
        stage("Building Code for Maven"){
            steps{
                sh 'mvn clean deploy'
            }
        }
    }
}
