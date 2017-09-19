<h1 align="center">Virtual Bank Statement (VBS)</h1>

## 1. Overview 
Through Midus support, VBS plays a major role wherein it allows Main System to authenticate each transaction (i.e. *Deposit*/*Fund Transfer*) made by a member to a supported company bank.

Our Main System gets notified once a transaction has been processed, commands Midus to connect to the bank through the use of triggered **"robots"**, and fetch its VBS back to Main System.

## 2. How does VBS work?
Once Midus transmits the VBS back to Main System, it will now cross-check all necessary criterias (e.g. *Account Name*, *Bank Account #*, *Reference #*, *Amount* and *Timestamp*) which will then be make use of to compare between the obtained VBS and the bank details.

If Main System confirms that the VBS and bank details has been well-validated, it will now proceed to credit the appropriate amount transaction to member's play wallet.
