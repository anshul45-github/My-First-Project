So, first we have this python file buffer.py, which was open to all, while mm.java couldn't be directly opened.
I couldn't keep it password-protected here and hence, I have given direct access here.

So, first of all when you run the buffer.py file, it asks for a password, which you'll have to crack using deobfuscating the code.

Through that password you get access to the java code.
For deobfuscating this code, you not only have to crack the key but also make a change in the code.

---------------In case, you are stuck somewhere, then at the end I'll list all the passwords and methods to deobfuscate the codes-----------------

**DETAILED EXPLANATION**

When you run the python code, it asks for a password. If you enter right password, it tells you the key to access the java code.
If you enter wrong password, it keeps on asking the password, until you enter the correct password.

As for the java code, when you run it, you get lyrics of an indian song (Tu Hai Kahan by AUR).
In these lyrics, somewhere there is password that you need to enter, it asks for the password unless you enter the correct one.
Though it doesn't actually asks, but you have to enter.

Now, the message you get is still unclear, for which you'll have to make some change in the code.

**ALL THE PASSWORDS**
1. Python code:- IMOCC_anshul
2. Java code:- DeobfImocc
3. Change made:- At the very last of code, change val to val^1
