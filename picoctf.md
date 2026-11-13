Undo (picoCTF, General Skills)
Step 0: Connect → nc <host> <port>
Step 1: Base64 encoded → base64 -d
Step 2: Text reversed → rev
Step 3: _ replaced with - → tr '-' '_'
Step 4: { } replaced with ( ) → tr '()' '{}'
Step 5: ROT13 applied → tr 'a-zA-Z' 'n-za-mN-ZA-M'

## Log Hunt (General Skills)
**Goal:** What did the challenge ask you to find? parts of a flag
**Steps:** What did you do, in order? (Start from opening the file in Notepad.) i downloaded the log they gave me but it appeared to be too long for me to use it in notepad,so i used wget in the workspace to download the file then used grep to filter all the flagpart and then i put them in order,
**Commands/tools:** Which commands did you use? (2 of them): grep and wget
**What I learned:** One thing you understand now that you didn't this morning. how to get the words youre looking for faster
