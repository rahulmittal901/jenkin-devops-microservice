//DECLARATIVE
pipeline {
agent any
 // agent { docker { image 'maven:3.6.3' } }
stages {
stage ('Build'){
steps {
//  sh 'mvn --version'
echo "Build"
}
}
stage ('Test'){
steps {
echo "Test"
}
}
stage ('IntegrationTest'){
steps {
echo "IntegrationTest"
}
}
} 
  post {
  always {
    echo 'Im awesome. I run always'
  }
  success {
    echo 'I run when you are successful'
  }
  failure {
    echo 'I run when you fail'
  }
    //changed
}
}
