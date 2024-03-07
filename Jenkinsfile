pipeline {
agent any stages 1
//
//
//
//
//
//
//
stage('Clone repository') {
steps {
checkout ([$class: 'GitSCM', branches: [[name: **/main']], userRemoteConfigs: [[url: 'https://github.com/Jatinsharma159/Jenkins-git']ll)
}
stage ('Build') {
steps {
build 'PES2UG19CS159-1'
sh 'g++ main.cpp -o output'
}
}
stage ('Test') {
steps 1
sh './output'
}
}
stage ('Deploy') {
steps 1
echo 'deploy'
}
}
｝
posti
failuref
error 'Pipeline failed'
｝
}
                                         }
