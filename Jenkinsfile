node{
  stage("scm checkout"){
    git 'https://github.com/shamathashetty/myapp'
  
  }
  stage("copile_package"){
    def mvnHome = tool name: '3.8.4', type: 'maven'

    bat "$(mvnHome)/bin/mvn package"
  }
}
