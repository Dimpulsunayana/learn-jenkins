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

stage('Hello1'){
steps{
 echo 'Hello sunnu'
}
}

stage('Hello2'){
steps{
 echo 'Hello giri'
}
}

}

post{
always{
echo 'sending mail'
}
}
}