# Red-Rabbit-V3.9

What is Red-Rabbit

Red-Rabbit is a massive framework written from<br>
perl, rust, bash, batch, ruby, and go-lang <br>
this project is a massive one and is written with <br>
alot of effort, this has taken me a long time to write<br>
as i have had issues with me OS being weird lol<br>
not only that but red-rabbit is a really fast penetration testing 
platform and multi tool for new and even experinced hackers 


well you might ask what can it do?<br>

it can<br>

`port scan a host`<br>
`port scan your network`<br>
`port scan a web host`<br>
`spawn Fake Acess points`<br>
`Commit DHCMP attacks`<br>
`test your connection`<br>
`run whois tracers`<br>
`DOS a host`<br>
`test if a url is xss injectable`<br>
`test if a web host is SQL injectable`<br>
`Fuzz a file sharing server`<br>
`Capture all network BSSID's in range`<br>
`Change your interface mode`<br>
`and more `<br>
<br>
LANGUAGES USED<br> 

BATCH, PERL, GO, BASH, RUBY (MAIN), RUST, PYTHON3, PYTHON2

this tool is inspired by one of my first ruby frameworks 
for ethical hacking and web/host discovery
that tool was named Rube-Ster which had alot 
of bugs and a shit ton of work that was thrown 
to the side, so i decided to start this project 
which is well Red-Rabbit, you may ask where 
did the name come from, well initally Rube-Sters 
name cam from ruby hence the Rube- and the ster 
came from a bunny i used to know and it was named mr booster
sadly he passed away, anyway hence the name ster
then red rabbit which is a name derived from the og name 


================
Why this tool? 
===============

this tool has alot of options now for choices such as 

wifi Death, Fake AP, web port scanners, host port scanners 
dns, whois, loggers, banner and title parsers, and is written 
from mainly ruby however utilizes, perl, rust, go, ruby, bash, and batch 
you will notice batch is for win32-64 installs and bash is used for linux installs 



=====================
why so many languages 
=====================
well i wanted speed, and since i am currently learning 
rust, c, perl, ruby, go, and batch i decided to put 
my skills to the very well known test 

i also wanted speed 

to parse the results of a title of the domain
and to grab it faster i used golang 

Go -> go-title.go

i also wanted better exception handeling and easy 
etsting, especially with net/http parsing and result testing 

so i used perl so i can throw the URl's into a list, parse them 
and get faster results for testing a internet or stable connections 
perl is also really good for formatting 

i wanted it to somehwta be cross platform 

so i used bash and batch for the installs 

==========
why rust?
===========

simply for faster current network host identification 

====================
why rust IP sniffing?
====================

rust is really fast and a really good language compared to golang 
sure golang is built from assembly but rust over all is faster 
when it comes to handeling, socks, networking threadings and more 
so i built a small IP sniffer from rust 

============================================================
why make the main file in ruby if other languages are faster
============================================================ 

well currently im reading a few books with ruby, and wanted to put 
my ruby skills to the test to see my limits, and ruby is alot better 
when it comes to offensive security tools with networking and sending
payloads over the network or even making something like a windows 
trojan, so i decided to use it 

if your still confused and want to debate then ask yourself 

why is the biggest exploitation framework and the most powerful (MSF/metasploit)
is 97% built from pure ruby? 

=================================== what can this tool do ======================

spawn fake ap's
deauthenticate clients off a network 
do whois domain tracing 
reverse a dns
launch DHCMP attacks 
Flood networks 
Port Scan Hosts 
Port Scan Web Hosts 
IP Parse 
Find ports on the local network 
check your current connection 
Scan the local area for BSSID's and ranges ( its unorganized )
Fuzz File Sharing Websites ( crash and exploit the servers )
Arp Spoof Clients off the current network 
AP scan 




=============================== REQUIREMENTS ========================
perl
python 
rust 
rustc
crates 
cargo 
cpan 
ruby
bash or batch 
golang 

service/script REQUIREMENTS for modules 

ruby ===

net/http
socket 
time 
awaite
optparse 
iw phy
timeout 
http party 
open uri
uri
whois 
whois-parser
colorize
tty-spinner
ruby-gems 
openssl

Go ====

a fucking os 
a sys 
fmt 
strings 
net/http
net/html 

perl === 
Ansi color 
socket 
Strict 
HTTP Tiny

rust === 
use std::env;
use std::process::Command;
use std::io::{self, Write};
use std::net::{IpAddr, TcpStream};
use std::str::FromStr;
use std::process;
use std::sync::mpsc::{Sender, channel};
use std::thread;


=============================== WARNINGS ====================

ME OR ANYONE WHO CONTRIBUTED OR GAVE IDEAS ARE 
RESPONSIBLE FOR YOUR DUMBASS MAKING DUMBASS DECISIONS 
WE HIGHLY DISCLAIM AGAINST USING THIS TOOL FOR MALICOUS 
ACTIVITY IF YOU HAVE A PROBLEM 


 
=========================================================== EXAMPLES AND DEMOS OF SCRIPTS ===========================================


MODULE CHECK 

`[~] Checking Mods Before Run`<br>
`[▇] Checking Module ... Done!`<br>
`[✅️] Module Found`<br>
`[▇] Checking Module ... Done!`<br>
`[✅️] Module Found`<br>
`[▇] Checking Module ... Done!`<br>
`[✅️] Module Found`<br>
`[▇] Checking Module ... Done!`<br>
`[✅️] Module Found`<br>
`[▇] Checking Module ... Done!`<br>
`[✅️] Module Found`<br>
`[▇] Checking Module ... Done!`<br>
`[✅️] Module Found`<br>
`
  
  
