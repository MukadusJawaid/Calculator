# Calculator

print("\t\t\t\t ~welcome user! to my calculator program~".upper())
print("\t\t\t\t  _______________________________________")

print()

e="e" 
c="c"
while c=="c" :
    print()
    o=(input("enter +,-,/ or * operator: ".title()))
    print()
    if o=="+":
        print("\t\tuser you've enter operator now we are going to perform addition!!".upper())
        print()
        n1=eval(input("Enter Number # 01: "))
        n2=eval(input("Enter Number # 02: "))
        print()
        ans=n1+n2
        print(n1, "+", n2, "=", ans)
        
    elif o=="-":
        print("\t\t user you've enter - operator now we are going to perform subtraction!!".upper())
        print()
        n1=eval(input("Enter a Number#01: "))
        n2=eval(input("Enter a Number#02: "))
        print()
        ans=n1-n2
        print(n1, "-", n2, "=", ans)
        
        
    elif o=="*":
        print("\t\tyou enter * operator now we are going to perform multiplication!!".upper())
        print()
        n1=eval(input("Enter a Number#01: "))
        n2=eval(input("Enter a Number#02: "))
        print()
        ans=n1*n2
        print(n1, "*", n2, "=", ans)
        
    elif o=="/":
        print("\t\tyou enter / operator now we are going to perform division!!".upper())
        print()
        n1=eval(input("Enter a Number#01: "))
        n2=eval(input("Enter a Number#02: "))
        print()
        ans=n1/n2
        print(n1, "/", n2, "=", ans)
    
    else:
        print("user !!! you entered wrong operator .".title())
    

    try: 
        print()
        if o=="-":
            print()
            n=(input("enter / operator to perfrom the given task: ".title()))
            if n=="/":
                print()
                n1=eval(input("Enter a Number#01: "))
                n2=eval(input("Enter a Number#02: "))
                print()
                ans1=n1/n2
                print(n1, "/", n2, "=", ans1)
            elif n=="+":
                print()
                print("user? did you just entered + operator! opps it can't be performed".title())
            elif n=="*":
                print()
                print("user? did you just entered * operator! opps it can't be performed".title())
            elif n=="-":
                print()
                print("user? did you just entered - operator! opps it can't be performed".title())
                
        elif o=="/":
            print()
            n=(input("enter - operator to perfrom the given task: ".title()))
            if n=="-":
                print()
                n1=eval(input("Enter a Number#01: "))
                n2=eval(input("Enter a Number#02: "))
                print()
                ans1=n1-n2
                print(n1, "-", n2, "=", ans1)
            
            elif n=="+":
                print()
                print("user? did you just entered + operator! opps it can't be performed".title())
            elif n=="*":
                print()
                print("user? did you just entered * operator! opps it can't be performed".title())
            elif n=="/":
                print()
                print("user? did you just entered / operator! opps it can't be performed".title())
            

    except ZeroDivisionError:
        print()
        print("\t\topps user! their is zerodivisionerror! try again".title())
    except TypeError:
        print()
        print("\t\t opps user! their is type error! try again".title())
    except SyntaxError:
        print()
        print("\t\t Opps user! their is syntax error".title())
    except NameError:
        print()
        print("\t Opps user! their is name error".title())
    
        
    print()
    c=input("enter C to continue or enter e to exit ".upper())
    print()
    if c==e:
        
        print("\t\t\t\t\t\t\t\t~thankyou!!!~".upper())
        print("\t\t\t\t\t\t\t\t\t __________________")
        print("\t\t\t\t\t\t\t\t\t|~by ##############|".upper())
        print("\t\t\t\t\t\t\t\t\t|__________________|")
