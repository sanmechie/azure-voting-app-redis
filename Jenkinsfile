@Library('https://github.com/sanmechie/JenkinsSharedPipeline')

pipeline{
    agent: any
    stages{
        stage ('Call library from another repo'){
            steps{
                    script {
                        helloworld()
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