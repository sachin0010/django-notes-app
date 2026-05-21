@Library("shared") _
pipeline{
    agent any
    stages{
        stage("Code"){
            steps{
                script{
                git branch: 'main',
                url: 'https://github.com/sachin0010/django-notes-app.git'
            }
        }
    }
        stage("Build"){
            steps{
                script{
                docker_build("notes-app" , "latest" , "sachin1010")
                }
            }
        }
        stage("Push to DockerHub"){
            steps{
                script{
                    docker_push("notes-app" , "latest" , "sachin1010")
                }
            }
        }
        stage("Deploy"){
            steps{
                echo "deploy code"
                sh "docker compose down && docker compose up -d"
            }
        }
    }
    
}
