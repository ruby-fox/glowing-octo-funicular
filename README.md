#glowing-octo-funicular
print ("Hello! What is your name?")
firstname = input()
print (firstname, ", is that right?")
if input() == "no":
        print ("What is your name?")


else: print ("That is a lovely name! What is your surname?")
surname = input()
print (surname, ", is that right?")
if input() == ("no"):
       print ("What is your surname?")


else: print ("That is a lovely surname. Hello, ", firstname, " ", surname)


print ("Do you have a middle name?")
if input() == "yes":
 print ("What is your middle name?")
middlename = input()
print ("Your middle name is ", middlename)
print ("Your full name is ", firstname, " ", middlename, " ", surname, "." )
print ("Your initials are ", firstname[0], ". ", middlename[0], ". ", surname[0], ".")
print (surname.upper, firstname)
   #print (middlename, ", is that right?")
    #if input == (no)
     #print ("What is your middle name?")


#else: print ("Your full name is ",  firstname, " ", surname, ".")
#print ("Your initials are ", firstname[0], " ", surname[0])
#print (surname.upper, firstname)

print ("Can I call you by a nickname?")
