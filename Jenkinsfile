pipeline {
    agent 
    stages {
        stage('build') { 
            steps {
                echo "hey am just build stage, i will build the package"
            }
        }
        stage('Test') { 
            steps {
                echo "this is testing phase, compiled source code is tested here using junit"
            }
        }
        stage('Deploy') { 
            steps {
                 echo "am deploying this war file to tomcat" 
            }
        }
    }
}
