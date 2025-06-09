node {
    stage('Checkout') {
        git url: 'https://github.com/neeva2102/maven-jenkins-project.git', branch: 'main'
    }
    stage('Build') {
        sh 'mvn clean install'
    }
}


