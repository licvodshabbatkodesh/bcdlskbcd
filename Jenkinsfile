pipeline{
    agent{
        node{
            label 'linux'
        }
    }
    environment{
        AWS_DEFAULT_REGION='us-east-1'
        AWS_SECRET_ACCESS_KEY = credentials('bcdlskbcd')
    }
    stages{
        stage('Hello'){
            steps{
                
                aws --version
                aws ec2 describe-instances
                '''
                
            }
        }
    }
}