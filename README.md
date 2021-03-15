# JavaEEAssignment2
"Implementation" of Login/Register using JavaEE
The username that was entered on Login and Register page will be displayed on Main page after you sumbit the from.
The Forms are calling the Post method for their corresponding servlets(LoginServlet and RegisterServlet)
and the doPost methods are forwarding the 'data' of Forms to the Main Page (index.jsp).
In the main page, there is a message "Hello" + username. If the username is null, message will be "Hello Guest"

# Java Assignment3
When reloading the pages the cookie parameters are appeared in Localhost Log (as in screenshot) and when submitting the form, request parameter(username) appears also.
If the request.getSession returns null, the corresponding message will appear, or vice-versa. 

# Screnshots are saved in "Screens" folder.
