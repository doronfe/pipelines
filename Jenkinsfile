pipeline{
    agent any
    stages{
        stage('Spellcheck'){
            steps{
                build job: 'Spellcheck_Pipeline'
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
        }

}
