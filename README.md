# assignment-3

print("Enter the parameter Color")

print("i)Green \nii)Yellow \niii)Red")

color=input()

if (color == "Yellow"):

    print("\nIt's a SQUARE")

    exit

elif (color == "Red"):

    print("\nEnter the parameter Dot")

    print("i)Yes \nii)No")

    dot=input()

    if(dot == "Yes"):

        print("\nIt's a TRIANGLE")

        exit

    elif(dot=="No"):

        print("\nIt's a SQUARE")

        exit

    else:

        print("\nInvalid Dot")

elif (color == "Green"):

    print("\nEnter the parameter Outline")

    print("i)Dashed \nii)Solid")

    outline=input()

    if(outline == "Dashed"):

        print("\nIt's a TRIANGLE")

        exit

    elif(outline=="Solid"):

        print("\nIt's a SQUARE")

        exit

    else:

        print("\nInvalid Outline")

else:

    print("\nInvalid Color")
    
    
    
    
    
    
    
    
    




print("Enter the parameter Age")

print("i)Youth \nii)Middle Aged \niii)Senior")

age=input()

if (age == "Middle Aged"):

    print("\nThe person will buy the computer.")

    exit

elif (age == "Youth"):

    print("\nEnter the parameter Student")

    print("i)Yes \nii)No")

    student=input()

    if(student == "Yes"):

        print("\nThe person will buy the computer.")

        exit

    elif(student=="No"):

        print("\nThe person will not buy the computer.")

        exit

    else:

        print("\nInvalid Student")

elif (age == "Senior"):

    print("\nEnter the parameter Credit Rating")

    print("i)Fair \nii)Excellent")

    credit_rating=input()

    if(credit_rating == "Fair"):

        print("\nThe person will buy the computer.")

        exit

    elif(credit_rating=="Excellent"):

        print("\nThe person will not buy the computer.")

        exit

    else:

        print("\nInvalid Credit Rating")

else:

    print("\nInvalid Age")
