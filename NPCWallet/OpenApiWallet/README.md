# NPCWallet Open Api V1
Programmatically interface with NPCWallet.com wallet.

# Contents
* <a href="#get-to-know-about-npcwallet-api">Get to Know About NPCWallet API</a>
* <a href="#getting-started">Getting Started</a>
* Creating Main Wallet Address
* Creating Sub Wallet Address
* Retrieve NPCoin Wallet Address
* Sending/Transfer NPCoin

# Get to Know About NPCWallet API
NPCWallet are devided into two domain
* NPCWallet.com
* api-NPCWallet.com

<b>NPCWallet.com</b>
<br>
NPCWallet.com is our main WEB-BASED Wallet System. All API request about wallet will through the NPCWallet.com database and verifier system. We develop NPCWallet.com using fully pHp codes and some of jQuery/ajax. Wallet system that we develop using sha1 and sha256 algorithm.

<b>api-NPCWallet.com</b>
<br>
api-NPCWallet.com is our main processor for API Request. This api-NPCWallet.com also using fully pHp codes.


# Getting Started
To use this API, you will need to apply for <b>API USER CODE</b> and <b>API KEY</b>. For exchanger, will create <b>API USER CODE</b> and <b>API KEY</b>.

To apply the <b>API USER CODE</b> and <b>API KEY</b> simplfy click the link below and fill-up application form:
<br>
<a href="https://docs.google.com/forms/d/e/1FAIpQLSe-tiyf0ffiowj7UrDlch1CZCxOuAtfEBLECUhTogsVXxLHhA/viewform?c=0&w=1" target="_blank">CLICK HERE</a>

Affer submiting the form, we will process the <b>API USER CODE</b> and <b>API KEY</b> between 1 to 5 working days and we will notify applicant about <b>API USER CODE</b> and <b>API KEY</b> via our official email.
  
# Creating Main Wallet Address
For creating Main Wallet for the API just need parameters as below:
* API USER CODE
* API KEY

Because of API USER CODE and API KEY already assign to specific API Holder, this two parameters will not be duplicated.
The Main Wallet Address only will create once and the API Holder need to take note for the response reply for this request and save it in API Holder database.

# Creating Sub Wallet Address
In our API, API Holder can create as many as they want Sub Wallet Address for their user. This Sub Wallet Address will be create under API Holder <b>API USER CODE</b> and <b>API KEY</b>.

