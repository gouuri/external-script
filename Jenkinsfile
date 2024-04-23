// Jenkinsfile
def common = load 'common.groovy'

pipeline {
    agent any
    
    stages {
        stage('Example') {
            steps {
                script {
                    // Use function from external script
                    common.greet('John')
                }
            }
        }
    }
}
