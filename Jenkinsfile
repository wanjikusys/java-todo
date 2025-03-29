pipeline { 
  agent any
  tools { 
    gradle "Gradle-8"
  }
  stages { 
    stage('clone repository') {
      steps { 
        git 'https://github.com/wanjikusys/java-todo'
      }
    }
    stage('Build project') {
  steps { 
    sh 'gradle build'
  }
}

  }
}
