pipeline{
    agent any
    triggers {
        pollSCM '*/2 * * * *'
}

    stages{
        stage('build'){
            steps{
                echo "building in progress"
                sh "cat index.html"
            }
        }
        stage('deploy'){
            steps{
                echo "deploy in progress"
            }
        }
    }
}