### Lab-Report-2---Servers-and-SSH-Keys-Week-3-
# Part 1
### First Message Addition

![Image](CSE15_SS_M1.png)

### Second Message Addition

![Image](CSE15_SS_M2.png)
### My Code 
(I based my code entirely off of the NumberServer.java file from wavelet)
![Image](String_Code_CS15.png)

### Methods:
![Image](String_Code_CS15class1.png)
#### public String handleRequest(URI url) : This method is called by the StringHandler class, if the path includes /add-message it checks for the 's=' query to append whatever string follows. If the query is invalid it outputs an error message. This method keeps track of the number of messages as an integer.

![Image](String_Code_CS15class2.png)
#### public static void main(String[] args) throws IOException: This method checks for a valid port number as an integer and starts the requested server to that port number, if invalid it outputs an error message.

# Part 2
![Image](Private_CS15.png)

#### The path to the *private* key:

> C:\Users\17606\.ssh\id_rsa

![Image](public_cs15.png)

#### The path to the *public* key:

>  /home/linux/ieng6/cs15lfa23/cs15lfa23bv/.ssh/authorized_keys

#### My login did not ask for my password!!

![Image](Without_Pass_CS15.png)


# Part 3

I learned that there are ieng6 accounts for students and staff at my  university that I can run and save files to. It is amazing that I am capable of running on a remote computer in the Basement Computer Lab!
In the future I know I will use this feature consistantly as it will allow me to work on multiple devices at ease. 
