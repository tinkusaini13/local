pipeline{
        agent any 
        stages{
            stage("git checkout") {
                steps{
                    git 'https://github.com/tinkusaini13/local' 
                }
            }
                stage("Check Git Version"){
                    steps{
                       git '--version'
                    }
                }
                stage("Create a Directory"){
                    steps{
                       mkdir  '/Jenkins-data'
                    }
                }
        }
}
