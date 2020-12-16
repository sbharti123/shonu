pipeline {
  agent any
  stages {
    stage('First_Job') {
      steps {
        build 'first_job_no_label'
      }
    }

    stage('Second_Job') {
      steps {
        build 'second_job_agent1_label'
      }
    }

  }
}