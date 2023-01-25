pipeline {
agent any
stages {
stage('Clone Git') {
steps {
git 'https://github.com/BThangaraju/Jenkins.git'
}
}
stage('Build Code') {
steps {
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
