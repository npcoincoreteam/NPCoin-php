# NPCWallet Open Api V1
Programmatically interface with NPCWallet.com wallet.
New update on 09-02-2018

# Contents
* <a href="#get-to-know-about-npcwallet-api">Get to Know About NPCWallet API</a>
* <a href="#getting-started">Getting Started</a>
* <a href="#creating-wallet-address">Creating Wallet Address</a>
* <a href="#retrieve-wallet-balance">Retrieve Wallet Balance</a>
* <a href="#sendingtransfer-npcoin">Sending/Transfer NPCoin</a>
* <a href="#tracking-transaction-id">Tracking Transaction ID</a>
* <a href="#retrieve-multiple-or-thousands-transaction-for-addresses">Retrieve Multiple or Thousands Transaction for Addresses</a>

# Get to Know About NPCWallet API
NPCWallet are divided into two domain
* NPCWallet.com
* api-NPCWallet.com

<b>NPCWallet.com</b>
<br>
NPCWallet.com is our main WEB-BASED Wallet System. All API request about wallet will through the NPCWallet.com database and verify system. We develop NPCWallet.com using fully pHp codes and some of jQuery/ajax. Wallet system that we develop using sha1 and sha256 algorithm.

<b>api-NPCWallet.com</b>
<br>
api-NPCWallet.com is our main processor for API Request. This api-NPCWallet.com also using fully pHp codes.


# Getting Started
To use this API, you will need to apply for <b>API USER CODE</b> and <b>API KEY</b>. For exchanger, will create <b>API USER CODE</b> and <b>API KEY</b>.

To apply the <b>API USER CODE</b> and <b>API KEY</b> simplify click the link below and fill-up application form:
<br>
<a href="https://docs.google.com/forms/d/e/1FAIpQLSe-tiyf0ffiowj7UrDlch1CZCxOuAtfEBLECUhTogsVXxLHhA/viewform?c=0&w=1">CLICK HERE</a>
<br>
For exchanger we will create the API KEY for you (no need to fill the form), just provide to us your domain name, email and server IP. Email to us at <a href="mailto:npcoin.international@gmail.com">npcoin.international@gmail.com</a>

After submitting the form, we will process the <b>API USER CODE</b> and <b>API KEY</b> between 1 to 5 working days and we will notify applicant about <b>API USER CODE</b> and <b>API KEY</b> via our official email.
  
# Creating Wallet Address
For creating Wallet for the API, needs 4 important parameters as below:
* API USER CODE
* API KEY
* EMAIL ADDRESS (one email can create one address only in same API)
* PASSWORD

Because of API USER CODE and API KEY already assign to specific API Holder, this two parameters will not be duplicated.
<br>
<a href="https://github.com/npcoincoreteam/NPCoin/blob/master/NPCWallet/OpenApiWallet/Sample-Create-Wallet.txt">Sample Create Wallet</a>
<br>
<a href="https://github.com/npcoincoreteam/NPCoin/blob/master/NPCWallet/OpenApiWallet/Create-Wallet.txt">REFER HERE FOR API RESPONSE</a>

# Retrieve Wallet Balance
In our API, API Holder can create as many as they want the Wallet Address for their user. This Wallet Address will be create under API Holder <b>API USER CODE</b> and <b>API KEY</b>.
<br>
To retrieve Wallet Balance only need 2 important parameters as below:
* WALLET_SECRET (auto generate when create the wallet above)
* PASSWORD (the password that mention in create wallet above)
<br>
<a href="https://github.com/npcoincoreteam/NPCoin/blob/master/NPCWallet/OpenApiWallet/Sample-Retrieve-Balance.txt">Sample Retrieve Balance</a>
<br>
<a href="https://github.com/npcoincoreteam/NPCoin/blob/master/NPCWallet/OpenApiWallet/Retrieve-Balance.txt">REFER HERE FOR API RESPONSE</a>

# Sending/Transfer NPCoin
Function sending/transfer NPCoin is very strict and need more security parameters so that only authorise person and owner of the wallet address only can make the sending/transfer.

Function sending/transfer need parameter as below
* Sending Address / Wallet From
* Receiver Address / Wallet To
* Wallet Secret
* Password
* Amount to transfer
<br>
<a href="https://github.com/npcoincoreteam/NPCoin/blob/master/NPCWallet/OpenApiWallet/Sample-Request-Sending.txt">Sample Sending/Transfer Request</a>
<br>
<a href="https://github.com/npcoincoreteam/NPCoin/blob/master/NPCWallet/OpenApiWallet/Sending-Transfer-Response.txt">REFER HERE FOR API RESPONSE</a>

# Tracking Transaction ID
For API User, every transaction have their own Tracking ID (start with TX capital letter).
We now developing new API, so for the retrieving Tracking ID's data, only done for single Tracking ID only. But we will upgrade for tracking Multiple Tracking ID.

Function Tracking Transaction ID only need parameter as below
* Tracking ID
<br>
<a href="https://github.com/npcoincoreteam/NPCoin/blob/master/NPCWallet/OpenApiWallet/Sample-Track-Tracking-ID.txt">Sample Tracking Transaction ID Request</a>
<br>
<a href="https://github.com/npcoincoreteam/NPCoin/blob/master/NPCWallet/OpenApiWallet/Track-Tracking-ID.txt">REFER HERE FOR API RESPONSE</a>

# Retrieve Multiple or Thousands Transaction for Addresses
For API User, now we already allowed User to Retrieve Multiple or Thousands Transaction for Addresses.
In this function only need the wallet address as parameter.

Sample PHP code & Response

* All transaction (IN/OUT)
<a href="https://github.com/npcoincoreteam/NPCoin/blob/master/NPCWallet/OpenApiWallet/Sample-Transaction-In-Out.txt">click here</a>

* All transaction (IN only)
<a href="https://github.com/npcoincoreteam/NPCoin/blob/master/NPCWallet/OpenApiWallet/Sample-Transaction-In.txt">click here</a>

* All transaction (OUT only)
<a href="https://github.com/npcoincoreteam/NPCoin/blob/master/NPCWallet/OpenApiWallet/Sample-Transaction-Out.txt">click here</a>
