pipeline {
  agent any

  stages {
    stage("Clone") {
      steps {
        echo "Cloning GitHub repo..."
      }
    }

    stage("Deploy") {
      steps {
        echo "Deploying HTML..."
        sh "mkdir -p /var/www/html/jenkins-demo"
        sh "cp index.html /var/www/html/jenkins-demo/index.html"
      }
    }
  }
}
