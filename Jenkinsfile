pipeline { 
    agent any 
    stages { 
        stage('Docker Build') { 
            steps { 
                bat 'docker build -t myapp .' 
            } 
        } 
        stage('Docker Run') { 
            steps { 
                bat 'docker run --rm myapp' 
            } 
        } 
    } 
}
