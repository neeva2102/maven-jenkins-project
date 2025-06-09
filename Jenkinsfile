node {
    stage('Checkout') {
        git url: 'https://github.com/neeva2102/maven-jenkins-project.git', branch: 'master'
    }

    stage('Build') {
        // Use the configured Maven tool
        withMaven(maven: 'Maven3') {
            sh 'mvn clean install'
        }
    }
}



