pipeline {
agent any
stages {
stage('Clone Git') {
steps {
git 'https://github.com/duston04/helloWorld.git'
}
}
stage('Build Code') {
steps {
sh "chmod u+x hello.c"
sh "gcc hello.c"
sh "./a.out"
}
}
stage('Test Code') {
steps {
sh "echo cc hello.c -o hello"
sh "echo ./hello.c"
sh "echo ./hello.c"
}
}
}
}
