pipeline{



agent any

parameters {
 booleanParam(name: 'job',
 defaultValue: true,
 description: 'checkbox parameter'
}


stages {


stage('echo'){
steps {
echo "hello ishan ${params.job}"
}
}



}

