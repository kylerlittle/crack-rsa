# crack-rsa

## Description
This program reverse engineers Rivest, Shamir, and Adelman's (RSA) cryptographic 
algorithm. It cracks a basic sample text for a class assignment. The program
runs in approximately 24 ms on my laptop for a public key which is 11 digits
long. The algorithm I used to find the public key's prime factors is not
very efficient; as such, it would not function very well on larger public keys.
However, the algorithm I designed to find the private key, assuming we already 
have the prime factors, is extremely efficient.