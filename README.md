CryptoBox
=========
blogpost http://zainadil.com/cryptobox/


![CryptoBox Image](/CryptoBoxIMG.jpg "CryptoBox")

##What

CryptoBox is an AES based Encyrption/Decryption app that utilizes 128-Bit AES for file encryption and decryption. Currenly all file formats are supported, but there's no support for folders/directories. CryptoBox utilizes PBKDF2 with SHA-1 with a million iterations to generate the AES key from the user password.

###Tech Stack

- Java6
- Java Cryptography Extension (JCE)
- Java Swing

###To Install

```java
javac CryptoBox/CryptoBox.java
```

###Running the Program 

```java
java CryptoBox/CryptoBox
```

###Notes
Make sure you run the program from a directory above or other than the directory that contains the class files

Here's why : http://docs.oracle.com/javase/tutorial/uiswing/start/compile.html
