pipeline{
    agent any
    stages{
        stage('hello'){
            steps{
                script{
                     env.x="dimmi"
                    def y=10

                    print "x=${x}"
                    print "y=${y}"

                    print x
                    print y
                }
                script{
                    print x
                }
            }
            stage('hello1'){
                steps{
                    script{
                        print x
                    }
                }
            }
        }
    }
}