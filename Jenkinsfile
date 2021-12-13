pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''a=$1
b=$2
c=$3'''
      }
    }

    stage('test') {
      steps {
        sh '''if [ $a == $b ]
then
if [ $a == $c ]
then
echo \'a,b,c are equal\'
else
echo \'a,b are equal but a is not equal c\'
fi
else
echo \'a is not equal b\'
fi'''
      }
    }

    stage('deploy') {
      steps {
        sh '1 1 2'
      }
    }

  }
}