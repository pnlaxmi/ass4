pipeline {

agent any

stages {

stage('Build') {

steps {
sh("""
                    echo this operation takes a long time
                    """)
// bat 'javac HelloWorld.java'
//   bat 'java -version'

}

}

stage('Run') {

steps {

bat 'java HelloWorld'
}
}
}
}
