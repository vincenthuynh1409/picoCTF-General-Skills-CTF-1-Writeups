# 🔐 (Problem Set 2) "Obedient Cat" Challenge

### Challenge Description:
- Category: **General Skills**
- Difficulty: **EASY**
- Write-up Date: **5/26/2026**

<img width="1275" height="453" alt="image" src="https://github.com/user-attachments/assets/ccfe39fe-c5f6-4e14-94b7-c904b529ca49" />

---
### 💡 Solution:

For the CTF challenges with CLI, I will be using Kali Linux CLI.

<img width="369" height="169" alt="image" src="https://github.com/user-attachments/assets/a37fd330-6563-4fa8-aeb3-3676a5cc5b68" />

> Above: Kali Linux Terminal

First, looking at the problem, they provide us with a downloadable file named "file".

Right click the embedded link and click "copy link address" to copy the file link into your clipboard.

<img width="275" height="245" alt="image" src="https://github.com/user-attachments/assets/547a0ed5-fed7-4161-957a-3ea0afd5b60c" />

Then, (according to the hints) to get the file accessible in your shell, you use the `wget` command:

`wget [file link]`

> `wget` command is simply used to download files from the web!

<img width="738" height="325" alt="image" src="https://github.com/user-attachments/assets/8d754751-8a0e-481d-921a-f7c2a54423a1" />

> To paste the link you copied from earlier, just right click and click "paste selection"

Press enter and the file will download (below):

<img width="370" height="323" alt="image" src="https://github.com/user-attachments/assets/cfbd4532-de20-43a2-8c19-6bb9a2ef131b" />

> So where is the downloaded file now?
>
> Do see the file, do the `ls` command
>
>  The `ls` command just 




<img width="367" height="383" alt="Screenshot 2026-05-28 122429" src="https://github.com/user-attachments/assets/e0f8b637-c789-4f45-9fd8-956d39304d49" />

The cat command







So the **final flag** is: `picoCTF{101010}`! 🎉

> copy and paste (or manually type) the final flag into the submission area to complete the challenge.
