pipeline {
  agent any
  stages{
    stage("master branch code") {
      steps {
        git 'https://github.com/swarupa1995/mavenproject.git'
      }
      stage("dev branch code"){
        steps{
          git branch: 'dev', url: 'git \'https://github.com/swarupa1995/mavenproject.git\''
        }
      }
    }
      
