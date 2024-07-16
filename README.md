i decided to write a how to use text :

1 - open your anaconda powershell
2 - if you are using additional enviroment you need to activate it  exmpl: conda activate ml1 
3 - you need to work in same zone, so go to your directory exmpl: cd C://user/..../..../..
4 - now we can get up our server which we made with fastapi and uvicorn. write to pwrshl: uvicorn MyServer:app --reload
5 - in the powershell screen yo will see a domain as " https://......./8000" . it works on 8000 port. now you can copy this url and visit the web site.
6 - but no one can see our page on the internet because we work on local host. we need to use staticaly or dinamic ip or use external server as we used: ngrok
7 - ngrok provides an short time visible web server on internet. like 1-2 hours
8 - to make it work , we need to install ngrok.exe
9 - after that just click on it.we can see a terminal screen , now there is 1 or 2 step to go end.
10 - go to ngrok.com and step up to downloading page. there is a special key for you. copy it and paste ngrok.exe terminal.
11 - everything saved. now write : ngrok http 8000 ---- with this ngrok will know which port should work.
12 - copy the given url and go to website.. booooomXxXx
