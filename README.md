#  Talisman

## talisman online clean server files

Get Ubuntu 14.04 32 bit then follw this instructions

Here you get details to connect your vps details ip and password 
so use secure shell to connect vps using ip username is root and password
***
```sudo apt-get update ```
***
```sudo apt-get install mysql-server ```
***
this will ask for set Database Password So Make Strong Password 

then star setting up server 

first of all 
***
```sudo apt-get install git -y ```
***

***
``` git clone https://github.com/yob-yob/talisman-server.git```
***
then

***
``` cd NewData && mv * ../ ```
***
```cd```
***
Open All``` .INI``` files from ```all folders``` and replace ```128.199.105.184``` this ip to ```your ip ```

then open ```db``` folder and file name ```db_server_user.ini``` and replace ```22021982``` to your ```sql database password``` 

***
``` sudo apt-get install p7zip-full -y ```
***

***
``` cd game && 7z x *.7z```
***
```cd```
***
then give execute permission to 

``` db -> db_server and guard  login -> login_server and guard game -> game_server and guard ```



***
```sudo chmod 755 db/db_server```
***



***
```sudo chmod 755 login/login_server```
***


***
```sudo chmod 755 game/game_server```
***

then also give same permission to file 1 2 3 

***
```sudo chmod 755 1```
***
```sudo chmod 755 2```
***
```sudo chmod 755 3```
***
then
***
```sudo dpkg -i *.deb ```
***
```apt-get -f install ```
***
```sudo dpkg -i lib*.deb ```
***
 don't forget to put your  *darkscorpio.evp*  in *game* folder i cant upload coz github dont support file larger then 25.MB 



and the last step to start server 


then

***
``` sudo apt-get install screen -y ```
***

*** 
``` screen -d -m ./1 ```
***

This will show nothing but wait 5 minutes

***
```  screen -d -m ./2 ```
***

This will show nothing but wait 
***
 ``` screen -d -m ./3 ```
***

 This will show nothing but your talisman server is online  and go play 
 
 
 
 if you like my help then donate as you like on paypal [Donate Me And Support me](https://paypal.me/Krushnadeep)
  For More Details Pm Me At [Himesh Patel](https://fb.me/darkscorpiont)  
 
 


