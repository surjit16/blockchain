# blockchain
We have created and identity authentication system based on blockchain technology
There is Three versions of the application-
1-	One is web app and we have hosted it on real time server.
2-	Client App - The mobile app of the same interface in android environment.
3-	Client App - Another third party mobile app for the user validation.
We have created and identity authentication system based on blockchain technology. The whole identity associated with user is inside the chain only and it has been encrypted with private key and public key pair. Public key will identify each user.
Identity Stands for – Name, Aadhaar Number, PAN card Number, License Number etc.
The whole information we can put in Block chain in encrypted form and for every user there is block and each user will be given a signature that will be unique always. And along with the signature will be converted into the QR code that will be given to the user for the certification purpose.
When the user will enter the information in the interface that have all the information that is needed to fill any form. The data is being stored in the chain in the encrypted form with the SHA256 algorithm with private key, public key pair. And after submission user will get the QR that can be further validated by the third-party app.


LINK to OUR PROJECT: 

1. https://github.com/surjit16/ClientInterface

2. https://github.com/surjit16/mobileBlockchain.git

3. https://github.com/surjit16/uidchain

Instruction to use-
-While using any of the app please do not use any firewall or proxy. Rather use mobile phone network (jio, airtel etc.)

-For creating new user user the uidchian or mobileBlockchain app. Evertime you are refreshing the interface you will be able to enter the   information for the other customer and user will be getting the QR for that. Then parallely all the chain content is going to a text     file and then we are retrieving the same file by parsing in json for the validation purpose.

- The ClientInterface will be used to validate the user by the QR assigned with the every individual user. it is being used to scan the QR and dynamically it is searching in the chain that the given signature exist or not.
