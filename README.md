# MCQ-with-Password-

pwd=input("Set your Password :")

max_attempt=3


for attempt in range(max_attempt):

    pwd1=input("Enter your Password :")
    if(pwd==pwd1):
        print("Start Exam")
        print("1. Who invented Java Programming?")
        print("1. ) Guido van Rossum")
        print("2. ) James Gosling")
        print("3. ) Dennis Ritchie")
        print("4. ) Bjarne Stroustrup")
        ans=input("Select Answer :")
    
        if ans=="2":
            print("2. Which component is used to compile, debug and execute the java programs?")
            print("1. ) JRE")
            print("2. ) JIT")
            print("3. ) JDK")
            print("4. ) JVM")
            ans1=input("Select Answer :")
            
            if ans1=="3":
                print("*******Congratulations All the  Answer are right *******")
            
            else:
                print("wrong answer [ Try Next year ]")
       
        else:
            print("wrong answer [ Try Next year ]")
        
        

    else:
        remain=max_attempt-(attempt+1)
        print(f"Wrong passwad... try {remain} More than {remain} ")





