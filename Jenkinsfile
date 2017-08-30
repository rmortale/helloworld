#!groovy

node {
  stage 'Checkout'
      checkout scm

  stage 'Setup'
      sh 'npm install'

  stage 'Cleanup2'
      echo 'prune and cleanup'
      sh 'npm prune'
      sh 'rm node_modules -rf'

}
