title: Example

# Example Challenge

!!! Important "Drive Link"
    [https://drive.google.com/drive/folders/1mlhMIM55BOkcyAJixuL1il21Ee6Oe97r?usp=sharing](https://drive.google.com/drive/folders/1mlhMIM55BOkcyAJixuL1il21Ee6Oe97r?usp=sharing)

## Challenge Description

Find the email and hotel of Mr. B. All we know is that his alias is THE4llANDP0werfu1MrB…. I hear he’s so eccentric he works with numbers in base 64!

!!! Question "Question:"
    How do we solve it? 

<details>

<summary>
Solution 
</summary>

- If we do a Google search for “THE4llANDP0werfu1MrB”, we get two results <br>
- One result is a Reddit link, which in the profile portion has a base64 encoded link <br>
- Using a base64 decoder, we can get the email <br>
- "Here's my email address: privateMailOfMrB@protonmail.com, but I will NOT reply in any way or form, so don't bother." <br>
- The other result is an Instagram profile <br>
- If we get the image of the only post (using inspect element), and reverse search the image on Google, we can get the name of the hotel <br>
- The hotel name is Bellagio

</details>

!!! Danger "IMPORTANT"
    Remember to submit your answers in **flag form**! 

<details>

<summary>
Flags
</summary>

This means that our flags are: <br>
PETCS{privateMailOfMrB@protonmail.com} <br>
and <br>
PETCS{bellagio}

</details>