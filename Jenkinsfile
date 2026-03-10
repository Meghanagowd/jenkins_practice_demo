pipeline {
agent any

stages {
    stage('Execute Python Script') {
        steps {
            echo "Starting Jenkins Pipeline"
            sh 'chmod +x script.sh'
            sh './script.sh'
            echo "Pipeline execution completed"
        }
    }
}

}
