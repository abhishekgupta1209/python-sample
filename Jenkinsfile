node{
  stage('Checkout') {
        
        deleteDir()
        checkout scm
    }
  stage ("Stage 1"){
    sh 'python3 --version'
    sh 'pytest'
    sh 'coverage run test_test1.py'
    sh 'coverage report'
    sh 'coverage xml'
  }
  
}
