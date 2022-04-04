pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "jenkins test"
            }
        }
    }
    post {
        changed {
            mail to "wangyijiewan@163.com" subject: "Jenkins test"
        }
    }
}