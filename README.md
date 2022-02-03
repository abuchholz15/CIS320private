# CIS320private
abuchholz@ubuntu20sever:~/git/Aden-s-Repository$ python3 udpclient.py
Input lowercase sentence to transmit (tx):Aden is a Networking God
TX: Aden is a Networking God
TO: ('', 12000)
...sent...
...waiting...
RX: ADEN IS A NETWORKING GOD
FROM: ('127.0.0.1', 12000)

abuchholz@ubuntu20sever:~/git/Aden-s-Repository$ python3 udpserver.py
The echo server is ready to recive and SEND BACK
...socket listening...press ctrl-c to quit
MESSAGE RXD:
 FROM: ('127.0.0.1', 55243)
 MSG :  aden is a networking god
MESSAGE TX:
 TO: ('127.0.0.1', 55243)
 MSG:  ADEN IS A NETWORKING GOD
...sent data to the socket...
...socket listening...press ctrl-c to quit
