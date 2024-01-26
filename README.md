# Security Oauth2, OIDC, JWT, Keycloak , SpringBoot

# Part 1: Keycloak, Jwt 

## Bullet Points :
### in this part we will cover the following topics:

- Download Keycloak 23
- Start Keycloak
- Create an Admin account
- Create a Realm
- Create a client to secure
- Create users
- Create roles
- Assign roles to users
- Using Postman:
    - Test authentication with the password
    - Analyze the contents of both JWT Access Token and Refresh Token
    - Test authentication with the Refresh Token
    - Test authentication with Client ID and Client Secret
    - Change the parameters of Access Token and Refresh Token

### Screenshots :

#### 1. In the following screenshot, i authenticated with the username and password and we got the Access Token and Refresh Token:
<img width="605" alt="i1" src="https://github.com/ACHRAFHED/TP7/assets/102471232/54999108-04fb-4ec2-a1eb-e8485144de98">


#### 2. In the following screenshot, i decoded the Access Token and we can see its content using jwt.io:
<img width="547" alt="i2" src="https://github.com/ACHRAFHED/TP7/assets/102471232/3c506385-f5ce-4f73-83b5-2070acfe89f7">



#### 3. In the following screenshot, i authenticated with the Refresh Token and we got the new Access Token and Refresh Token:
<img width="612" alt="i3" src="https://github.com/ACHRAFHED/TP7/assets/102471232/b42f3a7d-b686-4495-a0c6-c64ddaac37f3">


#### 4. In the following screenshot, i authenticated with the Client ID and Client Secret and we got the Access Token and Refresh Token:
<img width="608" alt="i4" src="https://github.com/ACHRAFHED/TP7/assets/102471232/1ca9b230-c224-49f7-8d49-d881c3e49c3f">


#### 5. In the following screenshot, i changed the capabilitie configuration in keycloak and now even with the client username and password we can't get the Access Token and Refresh Token so we need to use the Client secret and Client ID to get the Access Token and Refresh Token:
<img width="614" alt="i51" src="https://github.com/ACHRAFHED/TP7/assets/102471232/8311a853-9a3d-495b-8ea3-cb7614b24634">
<img width="608" alt="i52" src="https://github.com/ACHRAFHED/TP7/assets/102471232/dbb13dbf-ac1d-4f02-b213-9971455d6380">



# Part 2: SpringBoot, Keycloak, Jwt , Oauth2 


## Bullet Points :

-   Develop and secure a microservices-based application using OAuth 2, OIDC, and Keycloak:
    - Inventory service
    - Frontend Thymeleaf
    - Frontend Angular


### Screenshots :

#### 1. In the following screenshot, i consulted the customer service and i get the list of customers:
<img width="485" alt="i6" src="https://github.com/ACHRAFHED/TP7/assets/102471232/7943d7a9-12eb-4bc2-ae7d-2cf23af8daff">


#### 2. In the following screenshot, i added the webjar dependency to the pom.xml file so i can use bootstrap and jquery in my project:
<img width="611" alt="i7" src="https://github.com/ACHRAFHED/TP7/assets/102471232/05f916e4-6029-46ea-b111-b2be987869e4">


#### 3. In the following screenshot, i added the template dependency to the pom.xml file so i can use thymeleaf template in my project that contains the navbar and the footer:
<img width="613" alt="i8" src="https://github.com/ACHRAFHED/TP7/assets/102471232/140dcf9f-b8ae-4df2-ba72-6bf926abe000">






