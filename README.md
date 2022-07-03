# document_upload

first extract zip file than..

1st step

than open  otp_project\otp_project\codeogniter_proj\application\config\config.php

change the base url from line no 26 if you put this another folder inside htdocs 
$config['base_url'] = 'http://localhost/otp_project/otp_project/codeogniter_proj/';

#NOTE - I am using xampp here 

2nd step

update sql in database 
named - user_info (1).sql
I have provided inside document_upload folder 

3rd step 

open your localhost 
and go inside otp_project/otp_project/codeogniter_proj/

than you get those 2 button of admin for login 

4th step 

*admin*

click on the link "register for admin"
put your mobile number and click on 'sent otp' 
  youll get the otp to the provided number 
  #Note I have only 8 credit left for getting otp from free api 
  
  if you dont get otp on mobile than open your console you'll file your otp their 
  
  after that you'll redirected to the user screen and you'll find all the users their 
  
  and the button for 'add user' for adding the user  

*user*

  this is also same as admin but if admin creates a user than only we can login here through that number and on that number you'll get the otp and here is also same as   admin if credit not left than you can open console to find that otp 
  
  their you can find add document and list of document 





