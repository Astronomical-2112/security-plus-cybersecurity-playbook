 - Symmetric encryption

Symmetric encryption uses the exact same key on both sides to encrypt and decrypt.
When encrypting a file, it is common to use a symmetric key, and everyone with the key can decrypt the information.
The problem is that everyone needs the exact same key, you may not want that in many cases, 
end to end encrypted messaging doesn't work as well when you have to send a key in plain text. It is faster but much less secure.

 - Asymmetric encryption 

Asymmetric encryption requires everyone to have a private and public encryption key.
The public key is used by the person encrypting a message, and the private key is needed to decrypt the message.  
It is impossible to to decrypt with the public key, so the information is encrypted, without both parties needing to share the same key.
It is also possible to share keys publicly without defeating the purpose of encryption in the first place.