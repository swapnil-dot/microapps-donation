pipeline {

   agent any

   stages {
       stage('Build Dockerfile') {
           steps {
              sh 'echo "Running docker build and deploy commands.........."'
              sh "docker build -t web ."   
                    
           }
       }
}
