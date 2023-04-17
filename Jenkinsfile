pipeline { 
  agent any 
  triggers {
    pollSCM('*/2 * * * *')
  }
  stages { 
    stage('Example 2') { 
      steps { 
        echo 'Hello World' 
      } 
    } 
  } 
}
