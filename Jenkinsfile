pipeline {
    agent {
        node {
            label 'maven'
        }
    }
environments {
    PATH = "/opt/apache-maven-3.9.4/bin:$PATH"
}
    stages {
        stage( 'build code') {
            steps {
               sh 'mvn clean deploy'
            }
        }
    }
}
