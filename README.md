# Plague_server
Server for Plague Ransomware

This server is the C&C of the Plague Project.
It should use TOR to be anonymous.

It's role is :
- to get encrypted (by RSA algorithm) request
- to decrypt it
- to stock data sended by the ransomware in the database
- to generate the "decryptor" (the program that will decrypt the victim's files)
- to check in the blockchain if the victim paid the ransom
- to release the decryptor if the victim paid the ransom

If the victim didn't paid yet this message is showed :
https://user-images.githubusercontent.com/24431487/95126432-c9411680-0756-11eb-8b3c-202578d840c2.png

If the victim had paid, this message is showed :
https://user-images.githubusercontent.com/24431487/95126738-30f76180-0757-11eb-9286-10031df5a7ec.png
