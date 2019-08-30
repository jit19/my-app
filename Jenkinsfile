node{
    
    stage('SCM Checkout'){
        git 'https://github.com/jit19/my-app/'
    }
    
    stage('maven clean'){
        
        tool name: 'maven3', type: 'maven'
        sh 'mvn clean'
    }
}
