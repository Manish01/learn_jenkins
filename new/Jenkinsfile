pipeline {
	agent any

	stages {

    stage (ST1) {
      steps {
         echo "ST1"
         sh '''#!/bin/bash
               free -m
               sleep 2
            '''
      }

    }

    stage (ST2) {
       steps {
         echo "ST2"
         sh '''#!/bin/bash
               df -h
               sleep 2
            '''
       }
    }

    stage (ST3) {
       steps {
         echo "ST3"
       }
    }

   }
}
