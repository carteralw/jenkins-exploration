def testMap = ['cat':'Meow', 'dog':'Woof']
testMap.each { animal, animalSound ->
    println "${animal} has the sound ${animalSound}"
};

def shortCommit = sh(returnStdout: true, script: "git log -n 1 --pretty=format:'%h'").trim()
