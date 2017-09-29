pipeline {
  agent {
    dockerfile {
      filename 'a'
    }
    
  }
  stages {
    stage('build') {
      steps {
        sh '''#!/usr/bin/python
#coding:utf8
print "hello world"'''
      }
    }
  }
}