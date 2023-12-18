# OpenId Connect and OAuth 2.0 server in Asp.Net Core using OpenIdDict
+ [Articles in ASP.NET Core](https://github.com/Kharlap-Sergey/articles/)
+ [OpenID Connect using OpendIdDict](https://medium.com/@sergeygoodgood/openid-connect-and-oauth2-0-server-in-aspnetcore-using-openiddict-c463c6ebc082)
+ [Multi Tenant in ASP.NET Core](https://medium.com/@sergeygoodgood/multitenant-oauth-server-with-openiddict-and-multitenant-authorites-for-jwt-authentication-in-asp-c0f1764fff8a)
+ [Options Pattern in ASP.NET Core](https://medium.com/@sergeygoodgood/options-pattern-in-asp-net-core-easier-than-you-think-ff47b4e5bff2)

# Articles
Code samples for my articles: 
#
### [Options Pattern in Asp Net Core: Easier than you think!](https://medium.com/@sergeygoodgood/options-pattern-in-asp-net-core-easier-than-you-think-ff47b4e5bff2?sk=741a06773286a89ec052c8cc438f0c1a)
Explore the intricacies of the Options Pattern in ASP.NET Core, from configuration to validation, and gain a deep understanding of its powerful capabilities.

[Code sample for the story](Asp/OptionsPattern/)
#
### [Tenanted Options for Multitenant Applications in ASP](https://medium.com/@sergeygoodgood/tenanted-options-for-multitenant-applications-in-asp-f3df6b519020?sk=d75519a84086cb04bc5ebcfa6f69058a)
Discover advanced configuration management techniques in ASP.NET Core, tailored for multi-tenant applications, and gain a deep understanding of Tenanted Options

[Code sample for the story](Asp/MultiTenantOptions/src/MultiTenantOptions.Core)
#
### [Multitenant OAuth Server with OpenIdDict and Multitenant Authorities for JWT Authentication in ASP](https://medium.com/@sergeygoodgood/multitenant-oauth-server-with-openiddict-and-multitenant-authorites-for-jwt-authentication-in-asp-c0f1764fff8a?sk=90eae574a7e168129ec133e471701ee7)
Elevate your OAuth server's security with insights into implementing multi-tenant JWT authentication using OpenIdDict in ASP.NET, ensuring the utmost protection for your users' data

[Code sample for the story](Asp/MultiTenantOptions/src/OAuthServer)
#
### [Demystifying Authentication and Authorization in ASP.NET Core: Under the Hood](https://medium.com/@sergeygoodgood/demystifying-authentication-and-authorization-in-asp-net-core-under-the-hood-eb06839dbd7f?source=friends_link&sk=75204ead5dcc916e5503ac343e3bf88c)
Dive into the world of ASP.NET Core Authentication and Authorization.
#
### [OpenId Connect and OAuth2.0 server in AspNetCore using OpenIdDict](https://medium.com/@sergeygoodgood/openid-connect-and-oauth2-0-server-in-aspnetcore-using-openiddict-c463c6ebc082)
Build your own OAuth Server without Duendo IdentityServer!
#
Based on my passion for knowledge sharing, I'm doing this thing for absolutely free.
You can follow [me on Medium](https://medium.com/@sergeygoodgood) to don't miss my new publications.

#
### Notes
+ [Don't use the OAuth password grant type](https://www.scottbrady91.com/oauth/why-the-resource-owner-password-credentials-grant-type-is-not-authentication-nor-suitable-for-modern-applications)
```
POST /token HTTP/1.1
  Host: auth.example.com
  Content-Type: application/x-www-form-urlencoded

  grant_type=password
  &username=scott
  &password=ilovecats
  &client_id=s7CieS3lru4
  &client_secret=a1d8f7b4896b40989549d641aa3ffbdc
```
