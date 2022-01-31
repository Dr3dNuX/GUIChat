# GUIChat
GUI chatroom program with client and server written in python using sockets and tkinter

Welcome to the GUI chatroom program written in python this is a simple chatroom with a tkinter front end.

HOW TO USE THIS SOFTWARE:

step one clone the repo and download the files ‘server.py’ and ‘client.py’

![gitclone](https://user-images.githubusercontent.com/84602650/151821506-a59e4f0f-6769-48f3-b8fc-bbdaa1dfefc4.jpeg)

step two open the server.py file in your  favorite code editor and change the HOST constant variable to the host of your computer: local host or private ipv4 address. Then change the port number to any port number you want.

![serverip](https://user-images.githubusercontent.com/84602650/151821526-ba433795-65a0-4cee-9707-76988d2d4a84.jpeg)

Step three now run the server.py file using your python 3.X interpreter.
You should see server running in your terminal.

![serverrunning](https://user-images.githubusercontent.com/84602650/151821573-87eeebb0-03ac-4933-8498-18b358d17df9.jpeg)

Step four open the client.py file in your favorite code editor and change the HOST constant variable to the address of the server this can be your public ip address or private local host. For public remember to port forward your computer and associated port number.

![clientip](https://user-images.githubusercontent.com/84602650/151821620-7da68eed-576f-476e-9c5a-6b7ab9c53366.jpeg)

Step five now run the client.py file and you should be greeted with a username prompt enter any user name you like then press enter.

![usernameprompt](https://user-images.githubusercontent.com/84602650/151821669-fb37bf70-0cec-4217-bfbd-ca82a81364b6.jpeg)

Now you should be connected the server logs messages and the chat relays when a new user joins, you can send messages using the text box and send button and when you shut down the client it will close the socket and send a message to the server that the connection is terminated and close down the socket.

![chatboxserverlog](https://user-images.githubusercontent.com/84602650/151821780-d8e8ad4d-df2f-451a-b341-c2462d964ec1.jpeg)

![twoclientschatting](https://user-images.githubusercontent.com/84602650/151821823-d807b9ca-5f6c-4804-93ab-11418b13adde.jpeg)

![serverlogging](https://user-images.githubusercontent.com/84602650/151821847-ba842c8e-e5ae-4237-92ec-0d393920ed37.jpeg)
