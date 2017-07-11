# Securtiy_CodeSpace
This repo contains my projects related to Security/Cryptology

Lab1: Security: Modes of Operation
Sep 2016 – Sep 2016
###################
This project gave me hands-on experience with some of the concepts of symmetric ciphers. The project uses OpenSSL, 
a program and library that supports a wide range of cryptographic operations provided by Kali Linux.

The project involved creating a random 8-byte key and 8-byte IV used for DES operations and a random 16-byte key 
and 16 byte IV used for AES operations.

The project included comparing the behavior of the CBC and ECB modes of operation when encrypting image files.
Finally the project allowed me to compare the effects of data corruption on ECB, CBC, OFB and CFB modes of operation. 
After encryption I flipped a single bit of the file before the decryption to observe the impact of the corruption on each 
of the modes of operation stated above.

Lab2: Security: Hacking WPA2 Personal
Oct 2016 - Oct 2016
###################
This project involved launching an attack on a WPA2-protected Wi-Fi network to recover the passphrase (aka Pre-shared Key or PSK). 
With good old WEP completely broken, the gold standard in Wi-Fi security is now WPA2. Unlike WEP whose key can be recovered by 
simply capturing a lot of traffic and performing cryptanalysis on it, an attack on WPA2 is not guaranteed to succeed. 
The weak link under WPA2 is the passphrase, which can be broken if weak. No other attack on WPA2 is currently feasible.

*************************** IMPORTANT ***************************************************************************
Note that it is a federal crime to access a computing device without authorization or to exceed authorized access. 
For details, refer to the Computer Fraud and Abuse Act (18 U.S.C. 1030). Carrying out this kind of attack on any 
Wi-Fi network other than the one owned by you is a crime under state and federal laws!!!!!!!!!!!!!
*****************************************************************************************************************

Lab3: Security: Asymmetric Encryption
Oct 2016 - Oct 2016
###################
This project gave me hands-on experience with some of the concepts of asymmetric ciphers and how asymmetric
encryption relates to symmetric encryption. I used OpenSSL in a Virtual Machine (VM).

Lab4: Security: Creating and Using Digital Certificates
Nov 2016 - Nov 2016
###################
This project allowed me to explore the process of issuing digital certificates. Acting as a Certificate Authority (CA) 
who issues certificates to other entities. As a CA I created a self-signed certificate (i.e., a root certificate)
whose corresponding private key is used to sign certificates for your customers. The root certificate will be loaded 
into the browser so the client’s certificates can be recognized. The project gave me insights into how a real CA works.

Lab5: Security: SSL Strip Attack
Dec 2016 - Dec 2016
###################
This project involved launching a man-in-middle attack on tls/ssl. I used SSLSTRIP --- a tool that transparently intercepts 
HTTP traffic from a victim machine on a network, watches for HTTPS links and redirects, and then maps those links back into 
look-alike HTTP links.
