The project involves:
The application which provides a dynamically generated REST API. The API have a sufficient set of services for the selected application domain. The REST API responses conform to REST standards.
The application makes use of an external REST service to complement its functionality.
The application uses a cloud database for accessing persistent information.
In my Windows System,
Initillialy, I set the FLASK_APP environment variable to the path of main.py.
Execution is done by the command flash run.
We observed in browser the local host in port 127.0.0.1:5000/ which will provide the list of All the API URls and the type of methods the API can handle. These are not hard coded.
In order to test it, We can use POSTMAN where we can check all the CRUD features.
There is a user table where hash based authentication can be done.
In order to store the user details and the appplication specific information, a database has been implemented.

