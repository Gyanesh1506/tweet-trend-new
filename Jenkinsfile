pipeline{
    agent{
        label "MAVEN"
    }
    stages{
        stage("Checking out git repo"){
            steps{
                git branch: 'main', url: 'https://github.com/Gyanesh1506/tweet-trend-new.git'
            }
        }
        stage("Building"){
            steps{
                sh 'mvn clean deploy'
            }
        }
    }
}
