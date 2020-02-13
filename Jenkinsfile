stages{
    stage('vaildating stage'){
               steps{
                 withMaven(maven : 'maven_3_6_3'){
                    sh 'mvn clean validate'
                    }
      }
    }
    
     stage('compiling stage'){
               steps{
                 withMaven(maven : 'maven_3_6_3'){
                    sh 'mvn clean compile'
                    }
      }
    }
    
     stage('testing stage'){
               steps{
                 withMaven(maven : 'maven_3_6_3'){
                    sh 'mvn clean test'
                    }
      }
    }


}
