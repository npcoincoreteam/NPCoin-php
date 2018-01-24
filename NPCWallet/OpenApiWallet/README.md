# NPCWallet Open Api V1
Programmatically interface with NPCWallet.com wallet.

# Contents
* <a href="#get-to-know-about-npcwallet-api">Get to Know About NPCWallet API</a>
* <a href="#getting-started">Getting Started</a>
* <a href="#creating-main-wallet-address">Creating Main Wallet Address</a>
* <a href="#creating-sub-wallet-address">Creating Sub Wallet Address</a>
* <a href="#sendingtransfer-npcoin">Sending/Transfer NPCoin</a>

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
<a href="https://docs.google.com/forms/d/e/1FAIpQLSe-tiyf0ffiowj7UrDlch1CZCxOuAtfEBLECUhTogsVXxLHhA/viewform?c=0&w=1">CLICK HERE</a>

Affer submiting the form, we will process the <b>API USER CODE</b> and <b>API KEY</b> between 1 to 5 working days and we will notify applicant about <b>API USER CODE</b> and <b>API KEY</b> via our official email.
  
# Creating Main Wallet Address
For creating Main Wallet for the API just need
* API USER CODE
* API KEY

Because of API USER CODE and API KEY already assign to specific API Holder, this two parameters will not be duplicated.
The Main Wallet Address only will create once and the API Holder need to take note for the response reply for this request and save it in API Holder database.
<br>
<a href="https://github.com/npcoincoreteam/NPCoin/blob/master/NPCWallet/OpenApiWallet/Sample-Request-Main-Wallet.txt">Sample Create Main Wallet</a>
<br>
<a href="https://github.com/npcoincoreteam/NPCoin/blob/master/NPCWallet/OpenApiWallet/Create-Main-Wallet.txt">REFER HERE FOR API RESPONSE</a>

# Creating Sub Wallet Address
In our API, API Holder can create as many as they want Sub Wallet Address for their user. This Sub Wallet Address will be create under API Holder <b>API USER CODE</b> and <b>API KEY</b>.
<br>
<a href="https://github.com/npcoincoreteam/NPCoin/blob/master/NPCWallet/OpenApiWallet/Sample-Request-Sub-Wallet.txt">Sample Create Sub Wallet</a>
<br>
<a href="https://github.com/npcoincoreteam/NPCoin/blob/master/NPCWallet/OpenApiWallet/Create-Sub-Wallet.txt">REFER HERE FOR API RESPONSE</a>

# Sending/Transfer NPCoin
Fuction sending/transfer NPCoin is very strict and need more security parameters so that only authorise person and owner of the wallet address only can make the sending/transfer.

Fuction sending/transfer need parameter as below
* API USER CODE
* API KEY
* Amount to transfer/send
* Sending Address
* wallet_sec_code for Sending Address
* Receiver Address
* Fee (that decided by our side)
<br>
<a href="https://github.com/npcoincoreteam/NPCoin/blob/master/NPCWallet/OpenApiWallet/Sample-Request-Sending.txt">Sample Sending/Transfer Request</a>
<br>
<a href="https://github.com/npcoincoreteam/NPCoin/blob/master/NPCWallet/OpenApiWallet/Sending-Transfer-Response.txt">REFER HERE FOR API RESPONSE</a>
