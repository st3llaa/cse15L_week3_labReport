# Lab Report 2: Servers and Bugs
## Part 1: StringServer
writing a web server (StringServer) takes path in the formate shown below:
```
/add-message?s=<string>
```
This results in the concatenation of a new line (```\n```) and the <string> input after the =, resulting in a runnign string remembering previous input. 


```
⤇ javac Server.java StringServer.java 
⤇ java StringServer 4000
Server Started! Visit http://localhost:4000
```
