# Writeup Of The IndyCTF

Hi! My name is Prateek. i am a first year student enrolled in the electronics and communication department. I am gonna share my experience of the CTF challenges. 

# Hardware


## Hello Hardware 

This challenge took some time to get completed as I had to learn the working of logic gates. We just had to make the final output as high(1). I from the last and proceeded towards the first one. then put the values of to the simulation and then it gave the flag.

## Noice_UART

This challenge was not hard. I just converted the UART format to ASCII format and got the flag.

## 5niff--1t

Just used logic1 x to open the file and used an analyzer to get hex. Then multiplied the baud rate of the resulting conversation by 12 and got the flag.

## Baby_IR

Got the flag in splitted from in the code in simulation file. Just had to decrypt the lines of binary one by one and remove the junk line which were not in the code. Then just matched the hex I got from decrypting to the cases in the code of tinkercad simulation.

# Crypto 



## Transkey 

Used a cipher identifier to identify the type of cipher. Then solved the cipher and foun out the key that made sense and put it in the cipher and found out the flag.

# Wireless 



## 4chan's Favourite 

I put the .wav file in sonic visualizer and added a layer of spectrogram. Then after enlarging the graph, I found the image of Rick Astley.

## Murphy's Ghost 

I put the key file in sonic visualizer and added spectrogram and got COOPER. Then i decyphered the cyphertext file and used the key to decypher it and got the word matthewmcconaughey. Found out that was the flag.

## Some weird Stuff

Honestly, I didn't understand the problem, but found a similar problem on google. I just understood how they solved that problem and tried to solve this by somewhat similar method and it worked.

## Dots And Dashes 

Got the flag by decyphering the code that comes after the rickroll.

# Reversing 

## Easy As You 

This question was very tricky. I don't know if it was just me or with someone else also but I just could not figure out how to do the challenge. After seeing it so many times, I tried decompiling the main function in IDA. There I saw a code that was being XORed by 5. Then I looked up at google how to solve this thing. Then I tried solving it by using python. I created a string with the code and then created an empty list. Then I just entered the XORed value of the code into the list and then got the flag. I won't say that this challenge was easy.


## Baby_rev



# MISC


## IRC
Just joined the libera chat and got the flag there.

## Sanity Check - 2

Just filled the form and got the flag after filling it.

# Web 

## Inspeccionar_y_disfrutar

Got the flag using inspect element.

## Web Inspector 

Got the flag using inspect element tool only.

# OSINT


## Finding Joey

Reverse searched the image at google. Found out that the building was located in Canning town and the nearest bus station is Canning town bus station.

# Programming 

## (net) cat out of the bag  

Just entered the netcat command in the terminal and waited for the flag. In the end the flag was printed.


