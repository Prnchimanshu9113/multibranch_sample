pipeline {
    agent any 
    
    stages {
        
        stage("Hello code"){
            steps{
               
                echo 'Hello-World'
            }
        }
         stage("Change Readme.md"){
            steps{
                def branch = "fix"
                if (branch == "fix") 
                {
                sh 'cat README.md'
                }
            }
        }
}
}
