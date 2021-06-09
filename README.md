This is application ready RESTfull api having all http endpoints and includes authentication <br/>
Postman Collection link:https://www.getpostman.com/collections/d4414b3b85cdc29b0591
Evirnment variable to create:
  PORT=port no,for local you can add any port no., for deployment get it from envirnment
  SENDGRID_API_KEY->send grid api key
  JWT_SECRET->you can give anything,used for hashing passwords
  MONGOGB_URL->you database url
Steps:
  1.First create a user 
  2.if you created the user,no need to sign in as authentication token will be saved automatically
  3.if you want you can add a profile pic/avatar 
  4.now from create tasks you can create multiple/singl task,default value for completed will be false
  5.logout after your work is done
If you want to test the application,url->https://rohitkv090-task-manger-api.herokuapp.com/
