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
sh "cc hello.c -o hello"
sh "./hello.c"
}
}
stage('Test Code') {
steps {
sh "cc hello.c -o hello"
sh "./hello.c"
sh "./hello.c"
}
}
}
}
