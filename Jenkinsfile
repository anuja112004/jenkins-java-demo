pipeline{
  agent any

  triggers{
    githubpush()
    cron('H/5 * * * *')
  }
  stages{
    stages('Build'){
      steps {
        echo 'Build triggered by Github push or cron schedule'
      }
    }
  }
}
