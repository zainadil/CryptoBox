CryptoBox
=========
blogpost http://zainadil.com/cryptobox/


![CryptoBox Image](/CryptoBoxIMG.jpg "CryptoBox")

##What

CryptoBox is an AES based Encyrption/Decryption app that utilizes 128-Bit AES for file encryption and decryption. Currenly all file formats are supported, but there's no support for directories. CryptoBox utilize PBKDF2 with SHA-1 with a million iterations for generating the AES key from the user password.

##Tech Stack

Java 6

JCE (Java Cryptography Extension)

Java Swing

##To Install

```java
javac CryptoBox/CryptoBox.java
```

##Running the Program 

```java
java CryptoBox/CryptoBox
```
Make sure you run the program from a directory above or other than the directory that contains the class files

Here's why : http://docs.oracle.com/javase/tutorial/uiswing/start/compile.html
