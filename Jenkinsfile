pipeline {
    agent any
    stages {
        stage("Checkout") {
            steps { git url: "https://github.com/saiam12/cloud-lab.git", branch:"main"}
        }
        stage("Build") {
            steps { sh "docker build -t myflash:test ."}
        }
    }
}
