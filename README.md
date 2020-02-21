# choose-your-own-adventure
print "Hi, welcome to this interactive story! We are going to start by asking you a few questions!"
print "----------"

character = input("Would you prefer to play as yourself or a given character? ")
print "----------"

while character != "given character" and character!= "myself":
    print "Sorry, that wasn't a valid answer! Please try again."
    character = input("Would you prefer to play as yourself or a given character? ")
    print "----------"

if character == "myself":
    name = input("Please input your name or what you prefer to be called: ")
    print "----------"
    print "You will be playing as " + name + "!"
    print "----------"
elif character == "given character":
    print "You will be playing as Robin Willows!"
    print "----------"
    name = "Robin Willows"

