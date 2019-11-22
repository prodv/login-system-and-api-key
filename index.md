## Login system and API key generation

It was built using a [NodeJS package](https://github.com/braitsch/node-login).

The above package was installed locally and then the code was edited for **registration of user and login**. For **generating the api key** the code was added.

User just need to put a username and password to register.
After registration an API key was generated and assigned to the user.

The username is encrypted using AES-256.
API key is generated using SHA-256.
Above data is stored in MongoDB.
 
Screenshots can be seen below.

Login page
-----------

<img src="server-login.png" width="300" height="200">


Dashboard
-----------

<img src="dashboard.png" width="1000" height="300">
