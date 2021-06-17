# Spring-Oauth-Postgres

**Endpoints**

**To Generate Token:**<br>
URL: https://localhost:8080/oauth/token

Header:<br>
Authorization:Basic Generated_Authorization_Code

Body(form-data):<br>
grant_type:password<br>
username:user<br>
password:password<br>
client_id:clientId<br>
client_secret:clientSecret

**To Validate token:**<br>
URL: https://localhost:8080/oauth/check_token

Header:<br>
Authorization:Basic Generated_Authorization_Code
 
Body(form-data):<br>
token:generated_token_from_token_endpoint
  
