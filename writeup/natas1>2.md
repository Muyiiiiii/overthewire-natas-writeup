## walkthrough
1. Same thing, using **_password_** from prev challenge and provided **_username_** to log in:
   >Username: _natas2_
   >
   >Password: _TguMNxKo1DSa1tujBLuZJnDUlCcUAPlI_
2. The page returns:
   > _There is nothing on this page_
3. Inspect the page
4. Notice theres an image source with almost no purpose:
   ![image](https://github.com/Muyiiiiii/overthewire-natas-writeup-/assets/154893444/1c5d3333-222a-4c5e-93ee-0d1c842b14f3)

   > The img src could be a hint
5. Using that as a hint, we can perform certain trick by going to the directory through URL:
   > add _/files_ to the back of the URL
   >
   > **http://natas2.natas.labs.overthewire.org/files/**
6. And there we go, a secret file name **users.txt**
   ![image](https://github.com/Muyiiiiii/overthewire-natas-writeup-/assets/154893444/755a9eda-efc6-48ad-aa93-e6177fe3561a)
7. Clicking into it returns a list of **_password_** and **_username_**
   
   ![image](https://github.com/Muyiiiiii/overthewire-natas-writeup-/assets/154893444/a9867349-c002-4cf1-be07-4716fecad8ab)
   
   And there we have it, **_password_** for the next level
   > _3gqisGdR0pjm6tpkDKdIWO2hSvchLeYH_
