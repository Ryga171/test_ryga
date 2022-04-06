pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Git integration'){
            steps{
                echo 'Integrate from git'
                
            }
        }
        stage('Maven build'){
            steps{
                echo 'Maven build'
            }
        }
        stage('Deploy'){
            steps{
                echo 'Deploy using ansible'
            }
        }
        stage('Testing'){
             steps{
                 echo 'Testing'
            }
        }
    }
}
