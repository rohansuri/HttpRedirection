# HttpRedirection
Perform Man in the middle attack on a victim using ARP Spoofing. And redirect the victim's http request to any other preset http request set by the attacker!

<h3>Requirements</h3>
  <ul><li>Scapy<br>
  <li>Python<br>
  <li>Tkinter<br><br>
  
Works on Ubuntu, Fedora (all linux distros having Linux Netfiler system which is configured using iptables)<br>

Read the doc file in the project, to understand -
<ul>
<li>The concept of ARP Spoofing
<li>Explanation of iptables configuration
</ul>

<h4>Screenshots</h4>
![Alt text](https://github.com/rohansuri/HttpRedirection/blob/master/screenshot.png "GUI")

The redirect IP in the above image is of www.google.com

And the result when you "Attack!!!"
The victim tries to access codechef.com but is returned with google.com :)
(See at the bottom Waiting for google.com)

![Alt text](https://github.com/rohansuri/HttpRedirection/blob/master/capture.png "Attack")
