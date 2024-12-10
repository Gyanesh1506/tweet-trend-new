pipeline{
    agent{
        label "MAVEN"
    }
    stages{
        stage("Building Cod"){
            steps{
                sh 'mvn clean deploy'
            }
        }
    }
}
