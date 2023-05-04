node {
  stage("Clone the project") {
    git branch: 'main', url: 'https://github.com/INNOMIGHT/jenkins-pipeline-demo.git'
  }

  stage("Compilation") {
    sh "./mvnw clean install -DskipTests"
  }
}
