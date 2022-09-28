# FirstWebAPI

  Required steps for Creating a Base
Step 1 : Clone this repo to your PC and open with Visual Studio 2022
step 2 : Install Postman from this link "https://www.postman.com/downloads/"
step 3 : Start the web App on Visual Studio.
Step 4 : Start Postman.
Step 5 : Disable SSL certificate verification in Postman From File > Settings (General tab), disable SSL certificate verification.
Step 6 : When you started the web app in visual studio it pops-up with a local webpage copy the <port number> from there
  
   Required steps for adding/posting the data on the webpage
Step 1 : Create a new request on postman as HTTP Request.
Step 2 : Set the HTTP method to POST.//it is basically for writing the data on the webpage through an external location
Step 3 : Set the URI to https://localhost:<port number>/todoitems. For example: https://localhost:5001/todoitems
Step 4 : Select the Body tab --> Select raw --> Set the type to JSON.
Step 5 : In the request body enter JSON for any number of to-do items but it should be in a particular format
  the format is : { "name":"<name of the task>", "isComplete":<true or false> }
        example : { "name":"walk dog", "isComplete":true }
                  { "name":"Play chess", "isComplete":false }
                  { "name":"Cooked Food", "isComplete":true }
Step 6 : 
