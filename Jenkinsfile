pipeline {
    agent any
    tools {
        nodejs "NodeJs"
}

stages {
    stage("Checkout") {
        steps {
            checkout scm
        }
    }
    // stage("Install") {
    //     steps {
    //         bat "npm install"
    //     }
    // }
    // stage("Build") {
    //     steps {
    //         bat "npm build"
    //     }
    // }
    // stage("Test") {
    //     steps {
    //         bat "npm test"
    //     }
    // }
    stage("Execute") {
        steps {
            bat "node First.js"
        }
    }
}
}