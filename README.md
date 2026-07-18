# project-1
spam message detection 
<br>
# program to check if a message is spam
<br>
message = input("Enter your messsage :").lower()
<br>
<br>
spam_keyword = ["free", "win","won", "winner", "prize", "lottery", "click here","subscribe","offer","urgently","act now","urgently","money","earn cash prize","buy now ","bonus","cash","100% free","password","call now","apply now","act now","call now","hurry","OTP"]
<br>
<br>
is_spam = False
<br>
for word in spam_keyword :
<br>
    if word in message:
    <br>
        is_spam = True
        <br>
        break
        <br>
        <br>
    
if is_spam:
<br>
    print("This message is SPAM")
    <br>
else:
<br>
    print("This message is NOT SPAM")
    <br>
