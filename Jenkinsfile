pipeline {
    agent { label 'server2022'}
    environment {PATH = "${env.PATH}:C:\\Perl64\\bin:C:\Program Files\Git\bin"}

      stages {
        stage('Start mozi.bat') {
            steps {
               bat '''
               cd C:\\BATNIKI\\
               mozi.bat
               
               '''
            }
           
        }
        
         stage('Start reest.bat') {
            steps {
               bat '''
               cd C:\\BATNIKI\\
               reest.bat
               
               '''

            }
         } 
             
        
        stage('Start pybl_1.bat') {
            steps {
               bat '''
               cd C:\\BATNIKI\\
               pybl_1.bat
               
               '''
            }
           
        }
        
         stage('Start rdp.bat') {
            steps {
               bat '''
               cd C:\\BATNIKI\\
               rdp.bat
               
               '''

            }
         } 
        
      }
    }
