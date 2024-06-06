pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name s3bucket --template-body file://s3bucket-cloudformation-us-east-2-pl.json --region 'us-east-2'"
            }
        }
    }
}
