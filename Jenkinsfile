node {
    stage('Checkout') {
        git url: 'https://github.com/neeva2102/maven-jenkins-project.git', branch: 'master'
    }

    stage('Build') {
        withMaven(maven: 'Maven3') { // This name must match the one you set in Global Tool Configuration
            sh 'mvn clean install'
        }
    }
}
