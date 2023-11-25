pipeline {
  agent any
  stages {
    stage('Job1') {
      steps {
        sh '''pipeline {
    agent any

    stages {
        stage(\'Crear Archivo Hola Mundo\') {
            steps {
                script {
                    // Crear un archivo llamado "helloworld.txt" en Carpeta1
                    bat \'echo Hola Mundo > Carpeta1/helloworld.txt\'
                }
            }
        }
    }'''
        }
      }

    }
  }