# simple_rsa_cli
A simple implementation of the RSA algorithm
You could use the script in the following way:

```
python rsa_encrypter_decrypter.py
Enter a prime number (17, 19, 23, etc): 17
Enter another prime number (Not one you entered above): 23
Generating your public/private keypairs now . . .
Your public key is  (265, 391)  and your private key is  (441, 391)
Enter a message to encrypt with your private key: kevin
Your encrypted message is:
19910111882110
Decrypting message with public key  (265, 391)  . . .
Your message is:
kevin
```

