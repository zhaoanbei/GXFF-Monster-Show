pipeline {
    stages {
        stage('Build') {
            steps {
                docker login -u caozz0828 -p Aws@12345
                docker build -t caozz0828/monster:v1 .
                docker push caozz0828/monster:v1                
            }
        }
    }
}
