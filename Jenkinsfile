@Library('github.com/sanmechie/JenkinsSharedPipeline')_

pipeline {
    agent any
    stages {
        stage ('Call library from another repo'){
            steps{
                    script {
                        helloworld.helloworld()
                    }

            }
            post {
                success{
                    echo "success"
                }
                failure{
                    echo "failure"
                }
            }
        }
    }




}