## Welcome to Navegos QA ubuntu package manager repository!

<br />

*All the packages are distributed as is, and only for x86 64bits ubuntu focal OS system.* *(Probably more it will come at later time)*

<br />

**Instructions:**
<br />

*add the sign key to your trusted keys*
<br />

***`sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-key 10649EA8D069C51D`***
<br />

*or*
<br />

***`curl -fsSL https://apt.navegos.net/pub.key | sudo apt-key add -`***

<br />

**Available packages versions:**

* Golang
  * golang-1.15
* UASM
  * uasm-2.51

<br />

**Source Links:**
<br />

*add package as sudo*
<br />

***`sudo add-apt-repository "deb [arch=amd64] https://apt.navegos.net/ubuntu/(package version)/ $(lsb_release -cs) main"`***

*or*
<br />

***`echo "deb [arch=amd64] https://apt.navegos.net/ubuntu/(package version)/ focal main" | sudo tee /etc/apt/sources.list.d/(package version).list`***
<br />

*example*
<br />

***`sudo add-apt-repository "deb [arch=amd64] https://apt.navegos.net/ubuntu/golang-1.15/ $(lsb_release -cs) main"`***
<br />

*or*
<br />

***`echo "deb [arch=amd64] https://apt.navegos.net/ubuntu/golang-1.15/ focal main" | sudo tee /etc/apt/sources.list.d/golang-1.15.list`***
<br />
