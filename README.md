# encoding_decoding
# Hashing algorithm using python
import hashlib
# use Hashlib (SHA) to import a high security code for your message
#encoding
my_message = "Your password is sid26thJan".encode()
hash1 ="SHA-256",hashlib.sha256(my_message).hexdigest()
print(hash1)
# Decoding
hash2 ="SHA-256",hashlib.sha256(my_message).digest()
print(hash2)
