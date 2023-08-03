## History of Internet

<h3>How did it started?</h3> 
&rarr; In 1960s, The US Government they created a program ARPA. ARPA is known as Advanced research project agency. The US government develop something ARPANET was designed to connect various research institutions and enable them to share computing resources and research finding.
<hr>

## OSI Layer

<p align="center"><img alt="OSI" src="https://user-images.githubusercontent.com/51878265/206166710-cafe1502-ea85-433d-b4bd-6124f8110992.png"></p>

## LAN,MAN & WAN
<p align="center"><img src="https://rightinfoservice.com/assets/jpg/SERVICES/NETWORKING/LAN%20MAN%20WAN.jpg"></p>
&rarr;Lan stands for local area network. Which is use in small area ex- Room,Building.<br>
&rarr;Man stands for mentropolitan network. Network in a city called a MAN.<br>
&rarr;Wan stands for Wide area network. Country or across globe is called WAN.<br>

## TCP

&rarr;TCP is a connection-oriented protocol. It will ensure that data will reach its destination and it will not be corrupted on the way  Eg: email and file transfer

## UDP

&rarr;UDP in turn is not connection-oriented. UDP starts transmitting data immediately, without waiting for connection confirmation from the receiving side. When we do not care that 100% data is reachin or not. UDP does not guarantee reliable delivery of data.  


## Ports

&rarr;A virtual point where network connections start and end. So that multiple applications can communicate easily.

<p align="center"><img alt="Tcp port" src="https://user-images.githubusercontent.com/51878265/206188329-c5b10491-d39e-40ca-8369-1a9965559857.png"></p>


|Port Number| Process | Uses |
|:--:|:--:|:--:|
|80 | HTTP | |
|443| HTTPs| |
|3306| MySQl | |

To check which ports the system are using

```bash
netstat -a -b
```
## IPv4 and IPv6

<p align="center"><img src="https://academy.avast.com/hs-fs/hubfs/New_Avast_Academy/IPv4%20vs.%20IPv6%20What%E2%80%99s%20the%20Difference/IPv4-vs-IPv6.png?width=2750&name=IPv4-vs-IPv6.png"></p>
<li data-sourcepos="45:1-46:0">IPv4 consists 4 octets each has 8 bits</li><br><li data-sourcepos="45:1-46:0">IPv6 consists 8 octets each has 16 bits</code></li>

## URL (Uniform Resource Locator)

A unique identifier is used to locate a resource on the Internet. Lilke HTML, JS files.

### URL Breakdown

<p align="center"><img src="https://user-images.githubusercontent.com/51878265/206189760-ea426560-0d3c-4c5f-a8c4-b4f7c9d6f106.png"></p>

- Generally, the URL dosen't contains a port number in the string because it is by default. For eg, `google.com` or `google.com:443`

## Topologies

<p align="center"><img src="https://1.bp.blogspot.com/-w1ePOKkwYzw/X1HQA2fQqZI/AAAAAAAAJa8/PwgRTSAMsdwPu2xjwePizXqvpWgPQpRdACLcBGAsYHQ/s1200/Networking-Topology.png"></p>

&rarr;Bus : Every system in the bus topology are are connected to cord or backbone cable. <br>
&rarr;Ring : Every system will communicate one another.<br>
&rarr;Star : There is one controlling central device that is connected to all the computer. <br>
&rarr;Tree : It is a combination of bus and star topology. <br>
&rarr;Mesh: Devices have direct connections to all other devices. Every single computer is connected to every single computer.<br>
<!--<p align="center"><img alt="" src=""></p> -->
