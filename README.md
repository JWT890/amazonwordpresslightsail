# amazonwordpresslightsail
Lightsail is a good service to get started with AWS learning and following the cloud journey of learning and available on the AWS free tier and offers services from networking to storage based capabiliites. With this is providing documentation for how to set up a WordPress instance using Amazon Lightsail  

First step is to head over to the Amazon Lightsail site and you will be greeted by the Lightsail home page  

![image](https://github.com/user-attachments/assets/cd7d4f61-145d-4529-ba3d-9fb45a200409)  
You will then want to click Create Instance  
After that select the platform of Linux/Unix and WordPress as its blueprint  
![image](https://github.com/user-attachments/assets/1650fead-da5f-4cb9-b1f8-fb3d305966f2)  

Then you will want to choose the $5-$12 a month plan since its free for the 90 days. Also choose dual-stack network  
![image](https://github.com/user-attachments/assets/0699006f-410b-4072-834e-5b272f862a69)  

Then you will want to name the instance this will be TestSite1  
![image](https://github.com/user-attachments/assets/ea7cbaa6-3b44-4526-ac34-a7c1c9c6f23f)  

Second step after its setup is to click on connecting by SSH in the top right corner with the three dashes  
![image](https://github.com/user-attachments/assets/c0aa92f3-8c1f-4279-b89d-72c1730c9876)  

Click it to connect, afterwards a browser will pop up with the Linux instance  
![image](https://github.com/user-attachments/assets/c72d39e4-d70d-4cc0-ba31-f15c57029749)  

Then enter the following command to get the password:  
cat $HOME/bitnami_application_password. Save it for later.  

Third step is signing in on the admin dashboard of the website  
Type in a browser: http://yourPublicIPaddress/wp-login.php and replace it with your IP Address. You can find your Public IPv4 address by clicking the Wordpress site name on Lightsail  

Next step is to login on the instance website. For user logon, put user and for password put what you got from the Linux terminal to login.  
After that you will be greeted by the dashboard for the admin side.  
![image](https://github.com/user-attachments/assets/6001b906-7713-4bd5-a20b-563084bde7bb)  


