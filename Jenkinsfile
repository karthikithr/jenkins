pipeline {
  agent any
  stages {
    stage('RPMBuild') {
      steps {
        sh '''#!/bin/bash

for file in /home/thotak/iconrpm/*
do
        if [[ "$file" == *.spec ]];
        then
                cp $file /home/thotak/rpmbuild/SPECS
        else
                cp $file /home/thotak/rpmbuild/SOURCES
        fi
done'''
      }
    }
  }
}