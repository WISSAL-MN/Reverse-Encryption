# Reverse-Encryption-in-Python-3

1. The first function is called encryption, it takes as a parameter a message that will be encrypted, the function will start by taking a Cipher which is an empty character string.

2. Subsequently we will use an integer i which will take the size of the message, then we go through our message letter by letter and we give Cipher = Cipher + the index of the last box of the message then we add the penultimate box to it and so on until you have read the whole message from the end to the beginning.
