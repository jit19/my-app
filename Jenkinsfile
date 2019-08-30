node{
    
    stage('SCM Checkout'){
        git 'https://github.com/jit19/my-app/'
    }
    
    stage('maven clean'){
        
       def mvnhome = tool name: 'maven3', type: 'maven'
       sh "${mvnhome}/bin/mvn clean"
    }
    stage('maven install'){
        def mvnhome = tool name: 'maven3', type: 'maven'
       sh "${mvnhome}/bin/mvn install"
    
    }
    stage('maven-package'){
       def mvnhome = tool name: 'maven3', type: 'maven'
       sh "${mvnhome}/bin/mvn package"
        
    }
    
}
