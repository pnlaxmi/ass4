pipeline {

agent any

stages {

stage('Build') {

steps {
sh("""
                   
 bat 'javac HelloWorld.java'
   bat 'java -version'

}

}

stage('Run') {

steps {

bat 'java HelloWorld'
}
}
}
}
