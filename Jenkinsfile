pipeline {
  agent any
  options {
    skipStagesAfterUnstable()
  }
  stages {
    stage('Deploy to DOcker') {
      steps {
        sh "docker login -u anudeepreddys -p dckr_pat_Rakxneo2JbqnrvkvfbVkCxvNwXk"
        sh "kubectl apply -f "
      }
    }
  }
}
