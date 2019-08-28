pipeline {
agent any
 
tools{
maven 'maven3'
jdk 'java-1.8'
}
 
stages {
stage ("initialize") {
steps {
sh '''
echo "PATH = ${PATH}"
echo "M2_HOME = ${M2_HOME}"
'''
}
}
