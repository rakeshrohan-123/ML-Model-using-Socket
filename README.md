# ML-Model-using-Socket
We can even create ML model using Networking concept through which client side can give input for our ml model and returns predictions to client .server accepts request of client and ml model will be trained and predicted in server.
This model brings clear idea we can even built models using Networking Interfaces
use one more OS or andrio phone where you  can install any app to run client side program
#client side
import socket
s=socket.socket()
serevrip="give server ip"
serverport=give some port
s.connect((severip,serverport))
print(s.recv(1024))
data1=s.send(b'5.1,3.5,1.4,0.2')
here 4 floats values are input to our model sepal length,sepal width,petal length,petal width
Note : make sure you take of data type convertion bytes,string,floats you can observe how converstions in socket_ml file
