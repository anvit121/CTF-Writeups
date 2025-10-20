### Dark Encryptor

**Description**  

![alt text](files/image.png)

#### **Solution Steps:**
I started by trying simple commands to check if there is any command injection vulnerability.

```bash
; ls -la
```

![alt text](files/image1.png)

So I found the ```flag.txt```

Now to view that file i tried this command:

```bash
&& cat flag.txt
```
![alt text](files/image2.png)

But this didn't work. So I tried a different command:

```bash
; cat flag.txt
```
![alt text](files/image3.png)

Flag: ```THM{pgp_cant_stop_me}```