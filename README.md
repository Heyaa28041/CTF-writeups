# CTF-writeups
QUESTION 1:
Challenge Name: The Lying Detective 
Type - OSINT 
Description: 
Somewhere in the depths of ACM VIT’s Instagram posts lies a clue—a YouTube link to a scene from my all-time favorite show. I left it as a comment on a post about our biggest flagship event, but memory fails me. 
Your mission is to track down my comment, uncover the hidden link, and extract the flag from the message I left behind. 
Do you have the investigative skills to retrace my digital footsteps? 
Flag Format: ACM{leet_type_string}  
 
Answer: ACM{5h3rl0ck3d_1n_f0r_4cm} 

STEPS:
1. I tracked the instagram post mentioned in the challlenge and fount the youtube link https://www.youtube.com/watch?v=RlZUH2N9S3Q  in the comments.
2. Upon opening the link, I found the comment “To prove that you really know OSINT maybe try 0:24 on my name ~ACM”. His name was 4n71v3n0m. After this timestamp, Sherlock was mentioned and there is a tool in OSINT named Sherlock which can find all links related to the username 4n71v3n0m.
   
![Screenshot 2025-03-29 025921](Screenshot%202025-03-29%20025921.png)
   ![Screenshot 2025-03-29 173248](Screenshot%202025-03-29%20173248.png)

   
3. I began opening the links and got Letterboxd: https://letterboxd.com/4n71v3n0m as my under-research link.


![Screenshot 2025-03-29 173254](Screenshot%202025-03-29%20173254.png)


4. I pressed ctrl+ u to view the page source and searched for acm and then found the flag. Though, we can also find the flag if we scroll down the reviews. Hence, we found the flag.
   
![Screenshot 2025-03-29 173304](Screenshot%202025-03-29%20173304.png)
![Screenshot 2025-03-29 173311](Screenshot%202025-03-29%20173311.png)

5. Tools Used – 
1. Sherlock – To find links related to the given username across different platforms. 
2. Instagram 
3. YouTube 
4. Letterboxd  
5. Page Source (CTRL+U) 

 
