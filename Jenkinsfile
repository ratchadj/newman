pipeline {
    agent {
        docker { image 'postman/newman_ubuntu1404:2.1.2' }
    }
    stages {
        stage('Test API') {
            steps {
                sh 'newman run https://www.getpostman.com/collections/631643-f695cab7-6878-eb55-7943-ad88e1ccfd65-JsLv;'
            }
        }
    }
}
