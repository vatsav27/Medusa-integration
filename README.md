Task 1 – Integrate and Run medusa locally


Step one:
We have to install the prerequisites for this task. They are-
•	Git
•	Nodejs
•	PostgreSQL

 ![image](https://github.com/user-attachments/assets/6c4c7a7b-a1da-4bc7-be42-923190a1886b)
 ![image](https://github.com/user-attachments/assets/f1016b2d-c674-456d-be26-6de8e19e9658)
 ![image](https://github.com/user-attachments/assets/64024181-1b5c-4e54-88f6-c4e0f6aa276b)

Step two:

Now we have to install the Medusa cli.
we use this command for installing cli -- npm install -g @medusajs/medusa-cli 

![image](https://github.com/user-attachments/assets/4598d348-13a0-455d-9859-fbd5ef4e595a)
![image](https://github.com/user-attachments/assets/ad509758-a5b4-41b6-a8cf-4655036cde18)
![image](https://github.com/user-attachments/assets/fd9f1d11-788d-4ff2-9720-c8117d25b18b)

Step three:

Once Medusa cli is installed, we have to run commands to set up the Medusa backend.
We use the command : medusa new my-medusa-app
During this setup, it asks for the database configuration. We should select “change credentials” here to input our database.
Then cd my-medusa-app\
       medusa develop
  We can see the login screen http://localhost:7001/login page of the browser automatically.
  
Step four:

We use “npm run seed” to add sample seed data to our database.

Step five:

Now run “medusa develop” to run your application.

Step six:

Medusa application will be available now on the browser at http://localhost:7001/login
We can use a sample gmail and password to login into medusa.

![image](https://github.com/user-attachments/assets/b2cb119a-9cd5-459a-9488-0e75badaea45)

 

