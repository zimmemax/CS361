Communication Contract:

To request data from my microservice: Simply create a file called "run.txt". 
This can be done anyway you'd like but the python code implementation would be:

file = open("run.txt", "w/r/a/w+") <- the mode for the file does not matter, nor will you need to set the file object returned to anything.

To recieve data:

f = open("login.txt", "r")
    array = []
    array = f.readlines()
    res = []
    for sub in array:
        res.append(sub.replace("\n", ""))

    uname = res[0]
    pword = res[1]
    
^^^^^^

uname and password will contain the users username and password respectively.

UML Diagram:

https://docs.google.com/presentation/d/19rQSbAvrcbMLkKz_hG1qiLPcDR-Jv22v9vO_hvJi_jE/edit?usp=sharing



