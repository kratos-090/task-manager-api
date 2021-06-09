This is application ready RESTfull api having all http endpoints and includes authentication <br/>
Postman Collection link:https://www.getpostman.com/collections/d4414b3b85cdc29b0591<br/>
Evirnment variable to create:<br/>
  PORT=port no,for local you can add any port no., for deployment get it from envirnment<br/>
  SENDGRID_API_KEY->send grid api key<br/>
  JWT_SECRET->you can give anything,used for hashing passwords<br/>
  MONGOGB_URL->you database url<br/>
Steps:<br/>
  1.First create a user<br/> 
  2.if you created the user,no need to sign in as authentication token will be saved automatically<br/>
  3.if you want you can add a profile pic/avatar <br/>
  4.now from create tasks you can create multiple/singl task,default value for completed will be false<br/>
  5.logout after your work is done<br/>
If you want to test the application,url->https://rohitkv090-task-manger-api.herokuapp.com/
