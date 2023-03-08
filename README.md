<h1>Making Syslog Entries Readable</h1>


<h2>Description</h2>
In this lab, I learned to make Syslog entries readable. Syslog is a protocol used to send system log or event messages to a specific server.
<br />



<h2>Environments Used </h2>

- <b>Kali GNU/Linux Rolling</b> 

<h2>Utilities and Language </h2>

- <b>Terminal</b>

<h2>Program walk-through:</h2>

<p align="center">
Navigate to the Terminal window <br>
Enter the following commands <br>
"cd /var/log" (provides the primary log folder for Linux) <br>
"ls" (lists all files) <br>
<img src="https://i.postimg.cc/kX1QJ0kD/Screen-Shot-2023-03-07-at-6-32-52-PM.png" height="80%" width="80%" alt=""/>
<br />

  
  
<p align="center">
Enter the following commands <br>
"cut -c1-20 syslog" (displays the first 20 characters of the each log item in the file) <br>
<img src="https://i.postimg.cc/QdqJLBjG/Screen-Shot-2023-03-07-at-6-40-38-PM.png" height="80%" width="80%" alt=""/>
<br />



<p align="center">
Enter the following commands <br>
"cut -c21-60 syslog" (This displays the next 40 characters which generally includes the source of each log item) <br>
<img src="https://i.postimg.cc/XqhDCrpD/Screen-Shot-2023-03-07-at-6-44-24-PM.png" height="80%" width="80%" alt=""/>
<br />




<p align="center">
Enter the following commands <br>
"cut -d ":" -f1-3 syslog" (displays fields) <br>
<img src="https://i.postimg.cc/nrcCDL67/Screen-Shot-2023-03-07-at-6-47-28-PM.png" height="80%" width="80%" alt=""/>
<br />












