# CS4001_Chat_Example

To demonstrate the ease of implementing a secure communication method, I created a simple chat application using socket.io, express.js and openpgpjs. 

This application allows two people to connect and exchange messages. All messages are encrypted using PGP on the client side, before it ever leaves the sender's computer. The messages are only ever decrypted on the receiver's computer with the private key that is stored locally. This means that no data in transit or on the server can be decrypted or read. 

This web application was created for demonstration pupposes and is not a completed application. There are some bugs and missing features that would need to be fixed for production use.

A demo of this application is currently hosted at: [chat.stetson.me](https://chat.stetson.me)
