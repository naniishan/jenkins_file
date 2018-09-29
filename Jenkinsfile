pipeline{
agent any
parameters {
 booleanParam(name: 'job',
 defaultValue: true,
 description: 'checkbox parameter')
 choice(name: 'choice',
 choices: 'one\ntwo\nthree\nfour',
 description: 'choices')
}
stages{
stage('echo'){
steps {
echo "hello ishan ${params.job}"
}
}
stage('choice'){
steps {
echo "choices ${param.choice}"
}
}
}
}
