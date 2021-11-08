pipeline{
        agent any 
        stages{
            stage("git checkout"){
                steps{
                    sh 'git https://github.com/tinkusaini13/local' 
                }
            }
                stage("Check Git Version"){
                    steps{
                    sh 'git --version'
                    }
                }
                stage("Create a Directory"){
                    steps{
                    sh   'mkdir  /Jenkins-data'
                    }
                }
        }
}
