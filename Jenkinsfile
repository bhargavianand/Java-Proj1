pipeline {
    agent {
        label 'Master'
    }
    stages {
        stage ('SCM checkout-1'){
            steps  {
                            git 'https://github.com/bhargavianand/Java-Proj1.git/'

            }
        }
        stage ('Java execute') {
            steps {
                    sh label: '', script: '''javac Sample.java
                    java Sample'''           
                }
        }
    }
}
