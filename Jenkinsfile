pipeline
{
    agent any
    stages
    {
         stage ("Ejecutar comandos de CMD"){
            steps {
                echo "Ejecutando comandos de versiones ...."                
                bat 'java -version'
                bat 'git --version'
            }
        }
    }
}
