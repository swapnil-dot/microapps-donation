pipeline {

   agent any

   stages {
       stage('Build Dockerfile') {
           steps {
              sh 'echo "Running docker build and deploy commands.........."'
              sh "docker build -t web ."   
                    
           }
       }
      stage('Build Dockerfile') {
           steps {
              sh 'echo "Run the image"'
              sh "docker run -it -p 8000:8000 web"   
                    
           }
       }
}
