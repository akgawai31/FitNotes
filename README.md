# FitNotes
Steps to set up the project on your local machine:  
For zip downloads, unzip the folder and go to step 4.
1) Make a new folder.  
2) Initialize an empty git repository inside the folder by running the command "git init" in your terminal.  
3) Clone the repository using "git clone https://github.com/0008akshay/FitNotes.git".  
4) Move into the folder, set up a new virtual enviroment and activate it.  
   4.1) For making a new virtual enviroment, paste "python3 -m venv venv" and run it.  
   4.2) For activating it:  
        Windows:  
        i) Set-ExecutionPolicy Unrestricted -scope process  
        ii) .\venv\Scripts\activate  
        Mac OS/Linux:  
        i) source venv/bin/activate  
5) Install all the dependencies using "pip install -r requirements.txt".  
6) Set up the database by entering the below commands one by one sequentially in the terminal:  
   i) python  
   ii) from application import db  
   iii) db.create_all()  
   iv) exit()  

   if not work do above step in flask shell:
   ```
   i) flask shell
   ii) from application import db
   iii) db.create_all()
   iv) exit()
   ```
7) Set up the enviroment variables and run the app.  
   Windows:  
   i) $env:FLASK_APP = "main"  
   ii) flask run  
   Mac OS/Linux:  
   i) export FLASK_APP=main  
   ii) flask run  
   
   
  ![Screenshot (3)](https://user-images.githubusercontent.com/76953374/219940317-1cb23289-23af-45a1-a2d5-f33f8b9885ab.png)
  ![Screenshot (4)](https://user-images.githubusercontent.com/76953374/219940327-ce5a0767-c63c-44bd-8772-1e8ce4d91031.png)
  ![Screenshot (5)](https://user-images.githubusercontent.com/76953374/219940337-46d7b784-ab82-4a7b-a494-2d89bd175bbd.png)
  ![Screenshot (7)](https://user-images.githubusercontent.com/76953374/219940355-d5d67fea-3cf6-4dd9-80ea-e88624c2b0da.png)
  ![Screenshot (9)](https://user-images.githubusercontent.com/76953374/219940367-c6d77c6d-0c8e-4532-a337-edcf5065e341.png)
  ![Screenshot (11)](https://user-images.githubusercontent.com/76953374/219940385-686d3fa8-3314-4efe-8bc0-8251e8e56516.png)
  ![Screenshot (10)](https://user-images.githubusercontent.com/76953374/219940459-32e47492-e6ef-426e-86e5-1cd4daca517b.png)
