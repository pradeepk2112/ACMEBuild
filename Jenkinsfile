pipeline{
    agent any
    stages{
        stage('make_git_conn'){
            steps{
                git 'https://github.com/pradeepk2112/ACMEBuild'
            }
        }
        stage('checkout_pom'){
            steps{
                bat 'mvn clean install'
            }
        }
    }
}
