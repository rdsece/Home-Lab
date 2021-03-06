<p align="center">
  <img width="460" height="300" src="https://images-na.ssl-images-amazon.com/images/I/51SoJzZvfLL._SX258_BO1,204,203,200_.jpg">
</p>

# Home Lab
This repository holds the documentation for my home lab I've built up and guides for others wanting
to build their own home network. Building your own home network is the best way to learn and can be
much cheaper than you think.


### Network Diagram
This is my current network configuration.  I used Visio to create the diagram.
[NETWORK DIAGRAM](https://github.com/so87/Home-Lab/blob/master/simon%20network.pdf).

### Software Development Excellence
The best thing about having all of this equipment is being able to deliver high quality software.  Every piece of software I write goes through my own Jenkins pipeline.  This pipeline runs static code analysis tests to reduce the amount of bugs, vulnerabilities, and technical debt.  I also write my own mocha security tests with Mocha to ensure my architecture is secure.  Once all of these tests pass, the code gets merged into production, and automatically deployed.  See the diagram.
  [CODING PROCESS](https://github.com/so87/Home-Lab/blob/master/development-pipeline.pdf).
#### Deployment Process
<p align="center">
  <img width="1000" height="500" src="https://github.com/so87/Security-Lab-Manager/blob/dev/documentation/dev-deploy-process.PNG">
</p
If you like this and want to setup your own build and code scanning stack head with https certs look at my other [repository](https://github.com/so87/CI-CD-Secure-Pipeline)

### My Hardware
Below is the hardware I use to run my home network.  My network works great for my needs, 
but by no means could support several users.  Building a network for enterprise use is a different beast.
Define what you need and want from your home lab before even thinking about buying hardware. Do lots of research. Many hardware buying guides from bloggers and streamers spend way too much money.  For example, if you are only going to store
files and host your own website, it makes no sense to spend $3,000 on a server with 52 GB of RAM. 
It's tempting to buy the latest and greatest hardware.  Always: 1.Ready  2.Aim  3.Fire

Networking Equipment

| Function             | Name                       | Cost $  |
| -------------        |:-------------:             | -----:  |
| Router/Firewall      | Unifi USG                  | 112     |
| Switch               | Unifi 8 port POE Switch    | 102     |
| Wifi                 | Unifi UAC Pro              | 120     |
| Rack/Rails/Shelves   | 18U 19"                    | 170     |

Server

| Function             | Name                       | Cost $  |
| -------------        |:-------------:             | -----:  |
| Server               | HP DL 380 G7               | 100     |
| RAM                  | DDR3 SRAM 8GB x 6          | 16      |
| CPU                  | Xeon E5645 2.4 Ghz x 2     | 16      |
| Hard Drives          | 10 K SAS HP 300GB x 6      | 20      |
| External Storage     | 8TB Seagate                | 120     |
| UPS                  | Tripp Lite 1500VA          | 160     |

Wifi Hacking Practice

| Function             | Name                       | Cost $  |
| -------------        |:-------------:             | -----:  |
| Router/Wifi          | Netgear WNR1000v2          | 30     |
| Wifi Hacking Adapter | ALFA Networks AWUS036H USB 500mW    | 20     |
| Victum Computer      | Dell 8GB 2.4 Gz Win 7      | 0     |


### Configuration Guides(in progress)
[LINK](https://github.com/so87/Home-Lab/blob/master/Configuration%20Guides.md)

### Buying a Server and Hardware buying guide
 Use this [LINK](https://www.labgopher.com/) to buy servers.  It filters ebay for servers based on your inputs. <br />
 Reddit also has a great write-up for getting started <br />
 [Reddit Guide](https://www.reddit.com/r/homelab/wiki/buyingguide)
 
 Here is a great guide for making your own home NAS <br />
 [DIY NAS](https://blog.briancmoses.com/2017/03/diy-nas-2017-edition.html) 

# Community
This is a really great community for seeing what others do.  Great resource for building your
own homelab.  Becareful browsing this sub-reddit too much... it may make you buy expensive equipment. <br />
[Reddit Home Lab](https://www.reddit.com/r/homelab/)
