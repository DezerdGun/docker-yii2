Hi guys! i will show you how to up docker with yii2 for your company project!
Firstly, you Should  add localhost in your own "system32 host" i will drop it downstairs.

1)If you use Windows copy localhost from your docker file which you wrote in file then,you should open C:\Windows\System32\drivers\hosts -> put inside hosts file this
127.0.0.1   backend.tmp.loc
127.0.0.1   frontend.tmp.loc

2) git clone
3) open terminal cd desktop cd docker-yii2, docker-compose up --build enter
4) docker ls   <-  this command shows you status docker it works or not!
5)in order to create vendor folder write in terminal this commands -> docker ps -> choose php container and -> compose install 
6) inside container -> php init
7) at the end,  open browzer write there backend.tmp.loc/ or frontend.tmp.loc/

thats all thanks!

