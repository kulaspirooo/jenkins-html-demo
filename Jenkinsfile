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
        sh "mkdir -p jenkins-demo"
        sh "cp index.html jenkins-demo/index.html"
        echo "HTML copied to workspace directory."
      }
    }
  }
}
