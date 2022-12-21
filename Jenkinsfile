node{
  stage ("Stage 1"){
    sh 'python3 --version'
//     sh 'pip install coverage'
    sh 'coverage run test_test1.py'
    sh 'coverage report'
    sh 'coverage xml'
  }
  
}
