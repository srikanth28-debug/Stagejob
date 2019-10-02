pipeline{
    agent any
    stages {
        stage ('stage1'){
            steps {
                sh 'echo "Thi is first pipeline job"' 
            }
                
        } 
        stage ('stage2'){
            steps {
                sh '/usr/bin/sudo /usr/bin/yum install -y docker'
            }
        }
        stage ('stage3'){
            steps {
                sh 'sudo systemctl start docker'
            }
        }
        stage ('stage4'){
            steps {
                sh 'sudo docker pull ubuntu'
            }
        }
        stage ('stage5'){
            steps {
                sh 'sudo docker images'
            }
        }
            
    }
}
    
