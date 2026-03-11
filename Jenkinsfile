pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                
               git url: 'https://github.com/prasadprasii0803-ui/jenkins-simple-dem.git', 
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
