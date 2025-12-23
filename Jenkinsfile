pipeline{
    agent any
    }
    stages{
        stage("connect repo"){
            steps{
                git branch: 'main', credentialsId: 'github-creds', url: 'https://github.com/ilhamellyakhahar/vote-mikesir.git'
            }
            post{
                success{
                    echo "========connect repo executed successfully========"
            }
        }
    }
}