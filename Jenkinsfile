pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh'''#!/bin/bash
                groovy groovylib.groovy
                '''
            }
        }
    }
}
