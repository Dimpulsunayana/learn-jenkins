pipeline {
agent {
label 'dimpul'
}
stages{
stage('Hello'){
steps{
 echo 'Hello Dimpuldimmi'
}
}
}

post{
always{
echo 'sending mail'
}
}
}