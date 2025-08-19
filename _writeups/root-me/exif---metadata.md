---
layout: writeup
title: Exif   Metadata
ctf: root-me
category: steganography
points: 5
solves: Unknown
date: 2022-03-28
---

# Exif   Metadata (Root-Me, Steganography Category)

## Challenge Description
Our sad friend pepo got lost! Can you find where he is ?The password is the city where pepo is located.

## Solution
The challenge is to find the location of pepo .
### Approach
1. The challenge gives us a image file.![Exif   Metadata Screenshot](/assets/images/root-me/steganography/ch1.png).*no clue in the picture.*
2. let's check the metadata to find the location using exiftool.
```bash
Exiftool ch1.png
```
3. we get gps position in the metadata 43 deg 17' 56.27" N, 5 deg 22' 49.38" E that is the location of Marseille . Therefore the password is Marseille .


