# SocketClientDemo
This is a client-side socket demo built by CocoaAsyncSocket framework written in Swift4.
You can download and run it directly.

# Usage
![image](https://github.com/iwufan/Resources/blob/master/Images/Socket/Client-side.gif)

### 1. Input the IP address of the server.
### 2. Input the port of the server.
### 3. Click "开始连接".

After the server is connected with a client successfully, it can send messages to the client and receive messages from the client.

# Error
I you occur the error "No such module 'CocoaAsyncSocket'" as below.

![image](https://github.com/iwufan/Resources/blob/master/Images/Socket/CocaAsyncSocket_error.png)

You should know the project can run normally even this error exists.

Here are the methods to solve this error.

First, you should check whether you have installed CocaAsyncSocket framework through cocoapods.
If you have CocaAsyncSocket framework in you project, the solution will be very simple, just delete the words 'import CocaAsyncSocket' and type them again. 
Build the project and the error will disappear.

# Other
It's just a basic version. I will add more functions in future, like send images or musics to the server.

Enjoy, thanks.
