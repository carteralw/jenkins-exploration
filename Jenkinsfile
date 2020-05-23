node{
def testMap = ['cat':'Meow', 'dog':'Woof']
testMap.each { animal, animalSound ->
    stage("Test ${animal}") {
        shortCommit = sh(returnStdout: true, script: "git log -n 1 --pretty=format:'%h'").trim()
    }
};
}


