node{
  stage('git clone') {
    git 'https://github.com/vijaytambade/java-hello-world-with-maven'
  }
  stage('compile & build') {
    def mvnHome = tool name: 'maven 3.6.3', type: 'maven'
    sh "${mvnHome}/bin/mvn clean package" 
  }
}
