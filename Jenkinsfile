pipeline{
    agent {
        node{
            label 'built-in'
            customWorkspace '/home/ec2-user/garima'
        }
    }
    stages{
        stage('Production'){
            steps{
                sh '''
                   mvn clean install
                   '''
            }
        }
    }
}
