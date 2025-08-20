---
layout: writeup
title: Steganomobile
ctf: root-me
category: steganography
points: 10
solves: Unknown
date: 2011-04-29
---

# Steganomobile 

> After extracting the data from a mobile phone found at the scene of a crime, the investigators retrieved this series of figures... Maybe a phone number?

## Challenge Description
The challenge is to analyze the phone number looking txt file to get the flag.



### Approach
1. we are given text file that says 222-33-555-555-7-44-666-66-33

2. Taking the clue from challenge name i assume its related to a mobile phone. The text file given looks like  a Multi-tap ABC code .It is used in mobile phones to type text/SMS on keyboard with a numeric keypad.
![Steganomobile](/assets/images/root-me/steganography/Nokia_3210_3.jpg).*no clue in the picture.*
2. let's check the metadata to find the location using exiftool.
3. so with that when you tap number 2 thrice it writes 'C' ,when you tap number 3 twice it writes 'E'


