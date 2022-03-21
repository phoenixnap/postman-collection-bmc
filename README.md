
<h1 align="center">
  <br>
  <a href="https://phoenixnap.com/bare-metal-cloud"><img src="https://user-images.githubusercontent.com/78744488/109779287-16da8600-7c06-11eb-81a1-97bf44983d33.png" alt="phoenixnap Bare Metal Cloud" width="300"></a>
  <br>
  Postman Collection of Bare Metal Cloud APIs
  <br>
</h1>

<p align="center">
Interact with<a href="https://phoenixnap.com/bare-metal-cloud"> Bare Metal Cloud (BMC)</a> APIs using your favorite API management and testing tool. 
</p>

<p align="center">
  <a href="https://phoenixnap.com/bare-metal-cloud">Bare Metal Cloud</a> •
  <a href="https://www.postman.com/phoenixnap">BMC Collection on Postman</a> •
  <a href="https://developers.phoenixnap.com/">Developers Portal</a> •
  <a href="http://phoenixnap.com/kb">Knowledge Base</a> •
  <a href="https://developers.phoenixnap.com/support">Support</a>
</p>

## Requirements

- Bare Metal Cloud (BMC) account - [Get Started](https://learning.postman.com/docs/getting-started/installation-and-updates/)
- Postman account / locall installation of Postman - [View Instructions](https://learning.postman.com/docs/getting-started/installation-and-updates/)

## Creating a Bare Metal Cloud account

1. Go to the [Bare Metal Cloud signup page](https://support.phoenixnap.com/wap-jpost3/bmcSignup).
2. Follow the prompts to set up your account.
3. Use your credentials to [log in to Bare Metal Cloud portal](https://bmc.phoenixnap.com).

:arrow_forward: **Video tutorial:** [How to Create a Bare Metal Cloud Account in Minutes](https://www.youtube.com/watch?v=hPR60XWOSsQ)
<br>

:arrow_forward: **Video tutorial:** [How to Deploy a Bare Metal Server in a Minute](https://www.youtube.com/watch?v=BzBBwLxR80o)

## Creating Postman Account

To use Postman on the desktop, download the app and launch it.

Alternatively, navigate to Postman on the web at go.postman.co/home.

You will see a prompt to log in or sign up. Follow the steps outlined [here](https://learning.postman.com/docs/getting-started/installation-and-updates/) to create an account. 

## Using BMC Postman Collection

The Postman Collection of BMC APIs lets you easily trigger and test API calls to view your BMC server status, billing information, audit logs, networks, and tags. It is automatically updated on GitHub with every change we make to our APIs, so you always have the access to the latest version. 

**Deployment steps:**

  1. Download Collection from https://github.com/phoenixnap/postman-collection-bmc.
  2. Import the collection into Postman. 
  3. Set up two enviorment variables: clientId and clientSecret. <br>
      - Go to your Bare Metal Cloud acount and create Client Credentials with wanted scopes. Refer to the section below for detailed instructions on how to do it. <br>
      - Click *Manage Enviornments* in the top right corner of Postman inerface. <br>
      - Add two new environments with variables clientId (for Client ID) and clientSecret (for Client Secret) that you fetched from step BMC portal. <br>
      - Save the environment and select it in the environment drop down menu<br>
  4. The Collection can now be used to make or test API calls. 

**Authorization steps:**
  1. Go on the Collection.
  2. Click on the 3 dots button bottom right or right click.

![image](https://user-images.githubusercontent.com/94684424/159259149-cd62d058-876c-41e6-a786-0a6d9b227803.png)

  3. Go on edit.
  4. Go on Authorization.

![image](https://user-images.githubusercontent.com/94684424/159257108-69fecb30-29de-46f3-b587-6b0e3cf930bd.png)

  5. Get New Access Token.
  6. Click Update.
  7. You have generated a token which will be inherited by the individual calls. Repeat the process only for when the token expires.
 
:bulb: Parameters and Body Requests are provided as an example in all requests. They need to be changed to reflect your own use. <br>
:bulb: Environment variables you created for BMC credentials will not be deleted when you update the collection, even though everything else will be refreshed.   <br>

## Creating BMC Credentials 

Creating BMC Client ID and Client Secret takes several simple steps. 

  1. Log in to your BMC account at bmc.phoenixnap.com.
  2. Choose *API Credentials* from the left side menu.
  
  ![image](https://user-images.githubusercontent.com/81640346/140774465-99a4e248-0ca2-4927-80f2-2a2700256574.png)

  3. Click *Create API Credentials* to open a dialogue where you will enter Credential name and Credential description. 

![image](https://user-images.githubusercontent.com/81640346/140776688-57325239-10ba-4ae6-a9e8-5bdedbf67b2d.png)

  4. Select the Credentials scope and click *Create*. 
  5. Your Client ID and Client Secret have been created. You can copy them and add them to Postman as clientId and clientSecret for authorization. 

## Bare Metal Cloud community

Become part of the Bare Metal Cloud community to get updates on new features, help us improve the platform, and engage with developers and other users.

- Follow [@phoenixNAP on Twitter](https://twitter.com/phoenixnap)
- Join the [official Slack channel](https://phoenixnap.slack.com)
- Sign up for our [Developers Monthly newsletter](https://phoenixnap.com/developers-monthly-newsletter)

### Resources

- [Product page](https://phoenixnap.com/bare-metal-cloud)
- [Instance pricing](https://phoenixnap.com/bare-metal-cloud/instances)
- [YouTube tutorials](https://www.youtube.com/watch?v=8TLsqgLDMN4&list=PLWcrQnFWd54WwkHM0oPpR1BrAhxlsy1Rc&ab_channel=PhoenixNAPGlobalITServices)
- [Developers Portal](https://developers.phoenixnap.com)
- [Knowledge Base](https://phoenixnap.com/kb)
- [Blog](https:/phoenixnap.com/blog)

### Documentation

- [Postman Website - phoenixNAP](https://www.postman.com/phoenixnap)
- [API documentation](https://developers.phoenixnap.com/docs/bmc/1/overview)

### Contact phoenixNAP

Get in touch with us if you have questions or need help with Bare Metal Cloud.

<p align="left">
  <a href="https://twitter.com/phoenixNAP">Twitter</a> •
  <a href="https://www.facebook.com/phoenixnap">Facebook</a> •
  <a href="https://www.linkedin.com/company/phoenix-nap">LinkedIn</a> •
  <a href="https://www.instagram.com/phoenixnap">Instagram</a> •
  <a href="https://www.youtube.com/user/PhoenixNAPdatacenter">YouTube</a> •
  <a href="https://developers.phoenixnap.com/support">Email</a> 
</p>

<p align="center">
  <br>
  <a href="https://phoenixnap.com/bare-metal-cloud"><img src="https://user-images.githubusercontent.com/81640346/115243282-0c773b80-a123-11eb-9de7-59e3934a5712.jpg" alt="phoenixnap Bare Metal Cloud"></a>
</p>
