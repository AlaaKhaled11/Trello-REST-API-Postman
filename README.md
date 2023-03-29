# Trello-REST-API-Postman
# Install
● Download the collection files and import them into postman

# Notes
1. Create a workspace for "Trello"
2. Try any request like https://api.trello.com/1/members/me:
   <br> a. The response will be invalid token which means you don't have the authority to access this API <br>
  - b. So now you need to get your account credentials which will be sent with every request so the server will detect who you are and execute your request successfully
3. Get your credentials:
  - a. Log in to your Trello account
  - b. Get your personal key from here
  - c. If you got a "Trello Server Error: Oh no! 401!" when getting your personal key, make sure you are logged in Trello
  - d. On the same page, click on Token to get your token
  - e. After getting your credentials, you are now ready to start working on Trello's APIs
4. Explore all Trello's APIs from here
5. Submit a "credentials.txt" file with your app key and token
