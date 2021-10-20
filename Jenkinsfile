pipeline {
    agent any

    stages {
        stage('DRIVER PROJECT') {
            steps {
                echo 'Building..'
            }
        }
        stage('MOVEITEMTOCART') {
            steps {
                echo 'Testing..'
            }
        }
        stage('CHECKOUT001') {
            steps {
                echo 'Deploying....'
            }
        }
        
     
}


post {
            
            always{
                emailext body: 'PIPELINE EXECUTED SUCCESSFULLY.', subject: 'PIPELINE STATUS', to: 'selenium3sachin@gmail.com'
                
            }



}
}
