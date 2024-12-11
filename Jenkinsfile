pipeline{
    agent{
       node{
        label "MAVEN"
       }	
    }
    stages{
        stage("Building Code"){
            steps{
                sh 'mvn clean deploy'
            }
        }
    }
}
