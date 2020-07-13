# Setup Instructions for XAMPP


### For Windows PC


The instructions here is for a Windows PC. <br>
For Linux and Mac, it will be added later.


It would be better and preferrable if you install in a specific folder rather than the default path of
C:\xampp. 

<br>

i) Download the Xampp application from here : https://www.apachefriends.org/index.html
    The download size is around 150MB. 

<br>

ii) Create a folder in C drive and name it anything you want. <br>
    It is preferred if the maximum length of the folder is 8 characters.<br>
    For example, I am going to name it LEO.<br>

So, in C drive, there is a folder ARCHER.<br>
       
       C:\LEO

<br>

iii) Click on the downloaded application.<br>
        
![UAC](img/01_warning.png)

 <br>
You might see a warning like this. This was why I told you to create the folder. <br>
By creating our own folder, we need not worry about the permissions mentioned in that warning box.<br>
Now, click OK.<br><br>

iv) Click Next<br>

![UAC](img/02_step1.png)

<br>
v) By default, it would be <br>

        C:\xampp
        
  Change it to  <br>
  
        C:\LEO\xampp
   
  ![UAC](img/03_step2.png)
<br>

vi) If you want leave as it is and click next.<br>
But I don't want to know more about Bitnami.<br>
So, I am just unselecting it.<br><br>

![UAC](img/03_step3.png)

<br>
vii) Now, click Next.<br>
Just leave all the stuff as it is and let us install everything that XAMPP can provide. <br>
The installation will go on for 5 to 10 minutes depending on your system specifications. <br>

![UAC](img/04_step4.png)

<br><br>

viii) Click Finish.<br>

![UAC](img/05_step5.png)

<br>

ix) Select English.<br>

![UAC](img/06_step6.png)

<br>

x) And now the Control Panel is ready.

![UAC](img/07_step7.png)

<br>

We will be mostly using the _Apache_ and _MySQL_ server.

<br>

xi) Start the Apache and MySQL servers.<br>
You might get some message boxes like these.<br>

![UAC](img/08_warning1.png)

<br>

![UAC](img/08_warning2.png)

<br>

Just click _Allow Acess_.

Now, the _Apache_ and _MySQL_ servers are up and running.

![UAC](img/09_servers.png)
<br>

xii) Click on Admin of _Apache_ server. <br>
If all went fine, you should be seeing something like this: <br>

![UAC](img/10_apache.png)

<br>

xii) Click on Admin of _MySQL_ server. <br>
You will something like this: <br>

![UAC](img/11_phpmyadmin.png)

<br>

xiii) If one or both the servers didn't start, it might be because the same port might be used by some other application like VMWare or any other SQL servers. <br>
Based on experience, my advice would be not to tamper with the existing XAMPP config files. <br>
So, change the port number of the other applications. <br>
