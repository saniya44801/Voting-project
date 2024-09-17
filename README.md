print("Voting slot")
b,c,a=0,0,0
Age=int(input("Please enter your age"))
if Age>=18:
    print("Choose a political party:")
    print("Type 1 for BJP")
    print("Type 2 for Congress")
    print("Type 3 for AAP")
    choice=int(input("Choose a political party"))
    if choice==1:
        print("You voted for BJP")
        b+=1
    elif choice==2:
        print("You voted for Congress")
        c+=1
    elif choice==3:
        print("You voted for aap")
        a+=1
    else:
        print("Invalid")
else:
    print("Not eligible for vote")
print("Vote for BJP:",b)
print("Vote for congress:",c)
print("Vote for AAP:",a)

