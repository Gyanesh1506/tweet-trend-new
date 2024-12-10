pipeline{
    agent{
       node{
        label "MAVEN"
       }	
    }
    stages{
        stage("Building Cod"){
            steps{
                sh 'mvn clean deploy'
            }
        }
    }
}
