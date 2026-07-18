# project-1
spam message detection 
<br>
# program to check if a message is spam
<br>
message = input("Enter your messsage :").lower()
spam_keyword = ["free", "win","won", "winner", "prize", "lottery", "click here","subscribe","offer","urgently","act now","urgently","money","earn cash prize","buy now ","bonus","cash","100% free","password","call now","apply now","act now","call now","hurry","OTP"]
<br>
is_spam = False
for word in spam_keyword :
    if word in message:
        is_spam = True
        break
    
if is_spam:
    print("This message is SPAM")
else:
    print("This message is NOT SPAM")
