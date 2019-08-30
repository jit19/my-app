node{
    
    stage('SCM Checkout'){
        git 'https://github.com/jit19/my-app/'
    }
    
    stage('maven clean'){
        
       def mvnhome = tool name: 'maven3', type: 'maven'
        sh "${mvnhome}/bin/mvn clean"
    }
}
