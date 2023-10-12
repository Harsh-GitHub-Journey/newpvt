pipeline {
        agent { node {
          label 'Slave-SSH'
                      }
                  }

  stages {

    stage ('Env Variable') {
           step {
             echo "your build no is $BUILD_NUMBER"
           }
    }
        stage('Hello') {
            step {
              echo 'Hello World'
            }
    }
        stage ('GoodBye') {
      step {
        echo 'Have a nice day'
      }
        }

  }

}

    
    
          
