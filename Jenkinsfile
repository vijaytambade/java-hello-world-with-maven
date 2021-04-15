node{
  stage('git clone') {
    git 'https://github.com/vijaytambade/java-hello-world-with-maven'
  }
  stage('compile & build') {
    sh 'mvn clean package'  
  }
}
