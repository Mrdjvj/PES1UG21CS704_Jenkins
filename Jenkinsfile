pipeline {
agent any stages 1
stage ('Build') {
    steps {
        build 'PES1UG21CS704-1'
        sh 'g++ main.cpp -o output'
    }
}
stage ('Test') {
    steps{
    sh './output'
    }
}
stage ('Deploy') {
    steps {
        echo 'deploy'
    }
}

post{
    failure{
        error 'Pipeline failed'
    }
}
}
