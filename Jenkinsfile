pipeline{
    agent any
    parameters{
        string(name: 'sleep_time', defaultValue:'2', description:'time to sleep')
    }
    stages{
        stage('Pre-Build'){
            steps{
                echo 'Checking pre-requisites'
            }
        }
        stage('Linter'){
            steps{
                echo 'Static code analysis check'
            } // error app syntax --> fix the strings in app or bypass them
        }
        stage('Build'){
            steps{
                echo 'Building the Project'
            } // error with builds clean up 
        }
        stage('Test'){
            steps{
                echo 'Testing'
            }
        }
        stage('Pack the binary'){
            }
        }

}
