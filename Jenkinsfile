pipeline{
  agent any

  triggers{
    githubpush()
    cron('H/5 * * * *')
  }
  stages{
    stages('Build'){
      steps {
        echo 'Building the application '
      }
    }
     stages('Deploy'){
      steps {
        echo 'Deploying the application '
      }
    }
  }
}
