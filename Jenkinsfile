node{
  stage("scm checkout"){
    git 'https://github.com/shamathashetty/myapp'
  
  }
  stage("copile_package"){
    bat 'mvn package'
  }
}
