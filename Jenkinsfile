node(){
    //Test commit
    println "This is my jenkins job \n"   
    checkout([$class: 'GitSCM', branches: [[name: "master"]], userRemoteConfigs:[[url: "git@github.com:merqri/pythonTestCode.git", credentialsId: "GitHub_Cred"]]])
    sh 'python3 pythonCode.py'
}
