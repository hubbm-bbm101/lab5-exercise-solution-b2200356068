def email_check(email):
    if(".") and ("@") in email :
        return True

    else :

       return False

email = input("please enter your email")
if email_check(email) == True:
    print("Correct")

else :
       print("Wrong")
