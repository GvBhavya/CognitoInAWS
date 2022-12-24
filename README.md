# CognitoAngular

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.3.8.

Here is the demo to explain how to integrate Cognito with Angular application

what is Cognito : 
1.It is the authentication layer added  for users within  application.
2.We can set up the roles for each user to access the applciation pages.

How to setup Cognito in AWS :

1.Go to Cognito
2.Select 'Manage User Pools'
3.Click 'Create User Pool' button
4.Under name -> Give the pool name - 'demo-app-user-pool'
5.Under Attributes -> Select 'Email address or phone number' 
6.Under Policies -> Set password
7.Continue next steps and user pool get created
8.Next goTo 'AppClients' from sidenav
9.Add App Client
10.Go To - 'App Client Settings'  -> select 'Cognito user pools'
11.Under 'Oauth 2.0' -> Under 'Allowed OAuth Flows' -> select 'Authorization code grant'
12.Under 'Allowed OAuth Scopes',select email,openid
13.Choose Domain Name - > enter a unique domain name 
14.Once the domain is created,go back to 'app client settings', click on 'launchUI'
15.Copy and paste the URL in the application.
16.You are all set! 

<!-- HAPPY CODING -->
