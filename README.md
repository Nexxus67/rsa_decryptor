This is a Python program that demonstrates the use of RSA encryption, decryption, signing and verification.

When the program runs, it first generates a pair of RSA keys (a public key and a private key) of 1024 bits in length, and saves them to the files keys/publicKey.pem and keys/privateKey.pem, respectively.

Then, the program prompts the user to input a message to be encrypted and signed. The message is encrypted using the public key, and then signed using the private key.

The program then attempts to decrypt the encrypted message using the private key. If decryption is successful, the decrypted message is displayed. Otherwise, an error message is displayed.

Finally, the program verifies the message signature using the public key. If the signature is valid, a success message is displayed. Otherwise, an error message is displayed.
