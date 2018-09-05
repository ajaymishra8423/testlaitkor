pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
        stage('Build') {
       app = docker.build("laitkor/wordpress")
       {
         app.inside {
            sh 'echo "Tests passed"'
             }
           }
            
        }
      }
    }
  }
}
    

