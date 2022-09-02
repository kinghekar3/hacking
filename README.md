# hacking
Most 
GNU nano 6.3                GLITCH.py
import  socket
import sys
 from time  import *
 from datetime  import  datetime
#################
ip - input ( " === > ENTER YOUR IP TO START : " )
ti=datetime.now ( )
print ( " Scanning Start .. %=s Please Wait .. " %ip )
sleep ( 1 )
#################

try:

for port in range ( 1,6553 ) :
        s=socket.socket.AF_INET , socket . SOCK_STREAM ) )

        if(s.connect_ex ( ( ip , port ) )== 0:
         try:
            serv = socket.getservbyport ( port )

         except socket.error :

               serv="Unknown Service"

          print ( " Port %s Open Service : %s "% ( port ,serv))
       t2 = datetime.now ( )

     t3 = t2 - t1
     print ( " Scanning Completed On %s"%t3)
  except KeyboardInter

#################$#######################№$#########
