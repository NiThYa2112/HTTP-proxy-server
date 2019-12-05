# HTTP-proxy-server
Done by :Nithya Manoj, Hima Sajeev, Jayakrishnan B

An http proxy server written in C implementing  get requests using socket programming
It also contains provisions for caching, blacklisting and authentication

For running :
1. Compile the code
2. For execution ./a.out PORT_NO   // proxy server starts listening on the specified port no
3.For client side, telnet 127.0.0.1 PORT_NO   //establishes the connection 
4.For running the get request the format is GET url
