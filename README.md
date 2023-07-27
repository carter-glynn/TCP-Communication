# TCP-Communication <br>

## Goal <br>
 - Modify existing Microsoft TCP server code
 - Understand the workings of TCP and Telnet

## Description <br>
Create a TCP server to receive data. The server receives strings delimited by &. The program should display each received string on a separate line on the console. <br>
For example, if the received string is:<br><br>
abcdef&qwerty&123, <br>
the output is:<br><br>
abcdef<br.>
qwerty<br>
123<br><br>
The program prints each string as soon as it is complete (that is, an ‘&’ is found). <br>
Test the program by sending data using “Telnet.”