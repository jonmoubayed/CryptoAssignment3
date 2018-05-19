#CryptoAssignment3

##Names
* Jonathan Moubayed - jonmoubayed@csu.fullerton.edu
* Diego Franchi - diegofranchi@csu.fullerton.edu
* Imran Gosla - igosla0@csu.fullerton.edu
* Shree Rawal - Rawalshreepal000@gmail.com
* Chase Moynihan - chasemoy@csu.fullerton.edu
* Miles McCloskey - m.mccloskey@csu.fullerton.edu

##Programming Language 
Python

##How to Execute

To sign:
'''
python signer.py privKey.pem signature.sig input.txt sign
'''
* privKey.pem - The private key
* signature.sig - The signature
* input.txt - File that you want signed (one is included in the submission)
* sign - Identifier indicating the program to sign


To verigy:
'''
 python signer.py pubKey.pem signature.sig input.txt verify
'''
* pubKey.pem - The public key
* signature.sig - The signature
* input.txt - File that you want verify (one is included in the submission)
* verify - Identifier indicating the program to verify

##Extra Credit
No extra credit implemented 

##Special Comments
No special comments
