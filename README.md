<h1 style=>PP02. Chatroom</h1>

A chatting application

[Techologies] 

HTML, CSS, JS, PHP, MySQL, API. 

[Functionalities]

**1. Signup and Login/out**
   - signup page
    "Data varification"
    Invalid data can't be submitted.  
    ex) Existing ID, email address without '@'.
    <br/>
   - log in page
    "Waring message"
    Case1) ID & Password aren't matched.
    Case2) ID doesn't exist.
   <br/><br/>
   
**2. Private mode Chatting**
  A user can make his/her message visioble to only one person so that the user can talk <br/>
  to that another user privately.<br/>
  <br/><br/>
  
  *"How to chat in the private mode"*
  1. A user select another user to send a "private" message in the user list on the left side.
  2. Check the "Private" check box and type the message to send. 
  3. Click "Send" button. 
  <br/><br/>
  
**3. Choosing to read only unread messages**
  A user can choose to read only the messages that the user hasn't read or not.<br/>
   <br/>
   
  Procedure:
  1) A user click "Log out" button. 
  2) The app asks if the user wants to read only the unread messages.
  1) Click Yes/No in the question, if the user clickes "Yes", only unread messages'll show.
    If not, all messages'll be displayed. 
  <br/><br/>
 
 **"Convinent way" to see how this application works..**
 By importing the database("Back end/DB.sql") including the example dialogues & accounts
 you'll be able to see how the app works more easily and faster. 
 
 After importing the DB, you can log in with any of these accounts.
    Accounts(ID & password)
   admin   & adminpw   </br>
   sheldon & sheldonpw </br>
   leonard & leonardpw </br>
   howard  & howardpw  </br>
   laj     & lajpw     </br>
   </br></br>
   
Convenient way to see how **_"private mode chatting"**_ works: Use **_"leonard"**_ or **_"sheldon"**_ account.
Convenient way to see how **_"Choosing to read only unread messages"**_: Use **_"sheldon"**_ account.
   </br></br></br>


PS. The used dialogue is the part of the script of the season 01 episode 03 of "The Big Bang Theory".
