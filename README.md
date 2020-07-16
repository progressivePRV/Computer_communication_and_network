Note:-Use myserver.java and myclient.java in seprate folder, so that you can check for newly received or uploded files.

Below java program was written in openjdk 11

Use myserver.java using terminal/cmd/windows shell, using java as a command and same goes for myclient.java(in Clinet folder)

myserver.java will take one argument port number(advisable port number is greater than 5000).

myclient.java will take 4 arguments
1) IP address
2) port no.
3) command "GET" or "PUT"
4) filename to get
#IN THIS ORDER

You have to start first myserver.java with specific port number and try running myclient.java with GET and PUT methods
note:- provide localhost as ip address if you are running myserver.java ans myclient.java on same machine and also provide same port number you provided while running myserver.java

myserver.java will server files from folder where it is situated, i.e. as we have provided index.html in same folder it can serve it.
myclient.java will store requested file in same folder where it is stiuated.
myclient.java will only be able to put those files which present in same folder as myclient.java, i.e. index5.html can be used to test put method as it is in same folder.

myclient will only show response from server and myserver will only show request from clients.

Note:- To close myserver.java run closeServer.java program provided in Client Folder.
	closeServer.java program take two arguments 1)ip address and 2)port number.(In this Order)

You can make your own html files and try performing GET and PUT operationswith this programs.
