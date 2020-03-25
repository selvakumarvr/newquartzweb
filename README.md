# spring-boot-quartz-demo
Spring Boot + Quartz + Angular2 demo application. 

It explains how to schedule a cron job, how to pause a job, resume a job, edit quartz job etc. 
It used PostgreSQL as database for storing quartz jobs and triggers.

Detailed explanation: http://javabypatel.blogspot.sg/2017/10/quartz-scheduler-spring-boot-example.html

It contains UI application built on Angular2 for scheduling a job.
It also helps in Editing a job, you can also pause a job, resume a job, delete a job etc.

 ![output-image](https://1.bp.blogspot.com/-wdA6K1d_bj8/Wdun-8Sj7zI/AAAAAAAACIE/OXwEYjvnCWsHDaz7PGyLuzUr_jAiR6JagCLcBGAs/s1600/spring-quartz-scheduler-angular2-ui.PNG) 


http://javabypatel.blogspot.com/2017/10/quartz-scheduler-spring-boot-example.html


Go to "ui-app" folder and execute "npm install" command as shown below, (Make sure you have node and npm installed.)


Go to "ui-app" folder and execute "npm run server" command as shown below,


This step will start server and ui-app will be deployed.

Open the browser and hit http://localhost:8080/ you will see the application UI as shown above which will be used to schedule both simple and cron quartz job.

Start the Spring-boot application by clicking on "SpringBootQuartzAppApplication.java" > Right click, Run as, "Java Application"
Note: Server will be hosted on localhost and port as 7080. (http://localhost:7080/)