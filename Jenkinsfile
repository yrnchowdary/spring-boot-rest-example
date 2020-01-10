node{
  stage('SCM Checkout') {
  git 'https://github.com/yrnchowdary/spring-boot-rest-example'
  }
  stage('Compile-Package') {
  sh 'mvn package'
  }
}
