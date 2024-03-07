pipeline {
agent any stages 1
//
//
//
//
//
//
//
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
