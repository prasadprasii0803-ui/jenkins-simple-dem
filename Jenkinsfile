pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                
                 url: 'https://github.com/prasadprasii0803-ui/jenkins-simple-demo.git', 
                    branch: 'main'
            }
        }

        stage('Run Script') {
            steps {
              
                sh 'chmod +x script.sh'
                sh './script.sh'
            }
        }
    }
}
