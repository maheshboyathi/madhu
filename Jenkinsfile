pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''a=$1
b=$2
'''
      }
    }

    stage('test') {
      steps {
        sh '''if [ $a == $b ]
then
echo \'a equal b\'
else
echo \'a not equal b\'
fi
'''
      }
    }

  }
}