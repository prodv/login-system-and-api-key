## Login system and API key generation

It was built using a [NodeJS package](https://github.com/braitsch/node-login).

The above package was installed locally and then the code was edited for building **registration of user and login** feature. For  building the **generation of api key** feature the code of SHA-256 hash algorithm was added.

User just need to put a username and password to register.
After registration an API key was generated and assigned to the user.

The username is encrypted using AES-256 algorithm and stored in **MongoDB database**.

Similarly the API key was generated using SHA-256 and stored.

 
Screenshots can be seen below.

Login page
-----------

<img src="screenshots/server-login.png" width="300" height="200">


Dashboard
-----------

<img src="screenshots/dashboard.png" width="1000" height="300">
