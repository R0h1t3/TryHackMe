# CTF collection Vol.1
This is a writeup for the TryHackMe Room - CTF collection Vol.1

![image](https://user-images.githubusercontent.com/73820496/188527816-1b4355d3-2123-42c3-b5f3-c3cd1db9249c.png)

Off we go!!:computer:

## Task 1  Author note
Just another random CTF room created by me. Well, the main objective of the room is to test your CTF skills. For your information, vol.1 consists of 20 tasks and all the challenges are extremely easy. Stay calm and Capture the flag. :)

Note: All the challenges flag are formatted as THM{flag}, unless stated otherwise

## Task 2  What does the base said?
Can you decode the following?

`VEhNe2p1NTdfZDNjMGQzXzdoM19iNDUzfQ==`

### Solution
From the likes of it, this one looks like **Base64** Encyprion. Decoding this will produced the flag.<br>
My personal favourite, use [CyberChef](https://gchq.github.io/CyberChef/) for any encyprion/decryption techniques.<br>

How was I able to tell? Cipher ending with double equal to symbols are base64 encoded.<br>
**Tip:** Learn about tips to identify ciphers

## Task 3 Meta meta
Meta! meta! meta! meta...................................
<br>
This is a challenge with downloadable file. Download it.

### Solution
The downloaded file is in png format and it is a picture of the earth. Inherently there is no clue.<br>
But the from the name of the challenge and the file format. Our flag could be in the meta-data of the downloaded image.

**Tip:** Use Exiftool for finding the flag and search in all the values for the flag

## Task 4 Mon, are we going to be okay?
Something is hiding. That's all you need to know.
<br>
This is a challenge with downloadable file. Download it.

### Solution
Since its a picture, and there is **hiding** in the task description. This is a stegnography challenge.

**Tip:** USe tool called **StegHide** to solve the challenge

## Task 5 Erm...... Magick
This task has a direct flag!

## Task 6 QRrrrr
Such technology is quite reliable
