pipeline {
        agent { node {
          label 'Slave-SSH'
                      }
                  }

  stages {

    stage ('Env Variable') {
           steps {
             echo "your build no is $BUILD_NUMBER"
           }
    }
        stage('Hello') {
            steps {
              echo 'Hello World'
            }
    }
        stage ('GoodBye') {
      steps {
        echo 'Have a nice day'
      }
        }

  }

}

    
    
          
