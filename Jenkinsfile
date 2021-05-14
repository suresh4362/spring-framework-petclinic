node('MAVEN'){
   stage('git'){
     git 'https://github.com/suresh4362/spring-framework-petclinic.git'
   }
   stage('test'){
    sh 'mvn test'
   }
}
