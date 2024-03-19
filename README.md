# Luhn algorithm
_Welcome to Luhn algorithm repository! This project features a modulus 10 algorithm, which is a simple mathematical formula used to validate a user's identification numbers._


Table of Contents
-------------
1. [Introduction](#Introduction)
2. [Working](#Working)
3. [Output Preview](#Preview)

Introduction
-------------
   The Luhn algorithm, also known as the modulus 10 or mod 10 algorithm, is a simple checksum formula used to validate a variety of identification numbers, such as credit card numbers, IMEI numbers, Canadian Social Insurance Numbers.   
   The LUHN formula was created in the late 1960s by a group of mathematicians. Shortly thereafter, credit card companies adopted it. Because the algorithm is in the public domain, it can be used by anyone.   
   Most credit cards and many government identification numbers use the algorithm as a simple method of distinguishing valid numbers from mistyped or otherwise incorrect numbers. It was designed to protect against accidental errors, not malicious attacks.  

Working
-------------
The Luhn algorithm is as follows:

1. From the right to left, double the value of every second digit; if the product is greater than 9, sum the digits of the products.
2. Take the sum of all the digits.
3. If the sum of all the digits is a multiple of 10, then the number is valid; else it is not valid.

Assume an example of an account number "7992739871" that will have a check digit added, making it of the form 7992739871x:
<pre>
   Account number      7   9  9  2  7  3  9   8  7  1  x  
   Double every other  7  18  9  4  7  6  9  16  7  2  x  
   Sum 2-char digits   7   9  9  4  7  6  9   7  7  2  x  
</pre>

Preview
-------------
![luhn_valid](https://github.com/Rakshitha-ks/Luhn-Algorithm/assets/130575059/3fa05c51-1b59-485e-8d34-9af5cd53d4bb)

![luhn_invalid](https://github.com/Rakshitha-ks/Luhn-Algorithm/assets/130575059/b74634da-0b20-4a46-9ba8-b89f7731d8c9)

