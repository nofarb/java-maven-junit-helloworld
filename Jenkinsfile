pipeline {
    agent any
    stages {
          stage ("Build") {

                steps{
                        sh "./mvn test"
                    }   
            }
            stage ("Deploy to CloudFoundry") {
                    
                steps {
                    echo 'fake deploy'
                }
            }      
    }
}
