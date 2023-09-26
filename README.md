pipeline{
    agent any
    
    stages
    {
       stage('First stage')
       {
        steps
        {
            echo "Hi, This is first stage"
        } 
        }
        stage('second stage'){
            steps{
                echo"Hi, This is second stage"
            }
        }
        stage('Third stage'){
            steps{
                echo"Hi, This is Third stage"
            }
        }
        stage('Fourth stage'){
            steps{
                echo"Hi, This is Fourth stage"
            }
        }
        stage('fifth stage'){
            steps{
                echo"Hi, This is fifth stage"
            }
        }
    }
    
    
}
