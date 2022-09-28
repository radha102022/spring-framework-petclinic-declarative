node {
    stage("clone") {
       git 'https://github.com/spring-petclinic/spring-framework-petclinic.git'
    }

    stage("Build") {
        
      echo "build using mvn"
      sh './mvnw jetty:run-war'
    }
}
