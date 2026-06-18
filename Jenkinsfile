pipeline{
    agent any

    stages{
        stage("clone"){
            steps{
                git "https://github.com/saranyaAWS/junedemo.git"
            }
        }

        stage("build"){
            steps{
                sh "python3 --version"
            }
        }
        stage("deploy"){
            steps{
                sh "python3 app.py"
            }
        }
    }
}
