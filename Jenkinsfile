pipeline {
   agent any
   library identifier: 'demo-lib', retriever: modernSCM([$class: 'GitSCMSource', credentialsId: '0f0682df-26dd-48f2-86d4-40e2b48eabc7', id: '8c75cdf5-15e9-4288-949c-34ec894959a7', remote: 'https://github.com/SKT-Jenkins/mobile-rep.git'])
   stages {
      stage('Demo') {
        steps {
           hello 'Sanjay'
        }
      }
}

/* node{
   stage('SCM Checkout'){
     git 'git@github.com:SKT-Jenkins/mobile-rep.git'
   }
   stage('Compile code'){
     echo 'Compiling code stage working ok'
   }
} */
