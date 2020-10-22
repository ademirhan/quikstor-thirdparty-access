# Authentication

QuikStor use a standards-compliant OAuth 2.0 (https://oauth.net/2/) authorization server. Our implementation also allows users to manage their own connections.

If you are new to OAuth, you can read more at http://oauth.net. 

The authorization endpoint and the token request endpoint are https://api-test.quikstor.com/quikstor_online_api/Quikstor.Online.Authorization/Provider/OAuthProvider

#### Access Token
To make calls from our API you will need an access token. To get an access token you need to go through the access token flow and prompt the user to authorize by logging into QuikStor. Access tokens can be requested per user login. 

To begin, you will need to send the user to the authorization endpoint. Here’s an example request:

username=email@quikstor.com&password=typepassword&grant_type=password

{
  "title": "Authentication",
  "nested": {
    "id": 7,
    "siteId": true,
    "userId": Array[3][
      "list of",
      "fake strings",
      "and fake keys"
    ], 
    "token:: 0
  }
}

