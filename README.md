# Processing-Web-Server


## Стандартный и глючный файлик README.md А где искать эти -ВАУ :coffee: :pizza:, и :dancer:.  

Start out by downloading this processing project. (FYI it won’t compile as it is incomplete.) This project is a stub or starting point for your web server. It contains all the code for the setup and draw functions. What you need to implement are the Request and Response classes used in the draw function for handling the HTTP.  

You should start out by figuring out how the draw function uses the Request and Response objects. Then make a list of all the functions you think the Request and Response objects must implement. In addition, list out all the data that these objects must store. Finally, you need to figure out the algorithms for implementing the functions on these objects. For this final step you probably will need to refer to the reference material on HTTP.  

e.g. On the Request object, the valid instance variable is false by default. It only becomes true when the request string is parsed and proves to be a valid request string. To be a valid request string it must follow HTTP format. To see a valid request string use the Chrome browser Network developer tool to inspect the request and response headers.  

A couple of hints: The carriage return character and line feed character are \r and \n respectively. Use a HashMap<String, String> to store the header for both the Request and Response.  

Scope Limits
- You only need to handle GET requests.
- You don’t need to worry about the body of the request.
- You only need to handle 200, 404, and 500 http status responses.

