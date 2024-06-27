## walkthrough
1. Using **_password_** and **_username_** to log in into the page:
   > Username: _natas3_
   >
   > Password: _TguMNxKo1DSa1tujBLuZJnDUlCcUAPlI_ [from prev level]
2. Once logged into the page, the page returns.. again
   > _There is nothing on this page_
3. So again, inspect the source code to gather information
4. This time, the comment says:
   
   ![image](https://github.com/Muyiiiiii/overthewire-natas-writeup-/assets/154893444/fdd6a059-fac3-4ac0-a78b-3a5575445aff)

   So, theres a mechanism used to stop web crawlers from accessing certain websites, also known as **_robots.txt_**

   >For more info about **_robots.txt_**, https://developers.google.com/search/docs/crawling-indexing/robots/intro
6. By adding the **/robots.txt** to the end of the URL, we will be able to inspect the hidden webpages from website crawlers:
   >  _https://natas3.natas.labs.overthewire.org/robots.txt_
7. From there, we can observe and see that a directory named **/s3cr3t/** is hidden away
   
   ![image](https://github.com/Muyiiiiii/overthewire-natas-writeup-/assets/154893444/eab1a42b-eaf9-4f82-9fc4-9d65df9e9c04)

8. To access it, again, add it to the end of the URL
   > _https://natas3.natas.labs.overthewire.org/s3cr3t_
9. And there we go

   ![image](https://github.com/Muyiiiiii/overthewire-natas-writeup-/assets/154893444/e59dde76-022d-460b-9679-0b784c2eb5db)
10. Accessing the **users.txt** again, gives us the credentials for next level

    ![image](https://github.com/Muyiiiiii/overthewire-natas-writeup-/assets/154893444/89a0cf4b-b60a-4874-8ab4-a63c5a319e2c)

