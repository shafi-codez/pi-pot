# pi-pot
RasPberry PI Code Pot codes all my best knowledge and snippets

### Install Samba

[Samba/CIFS](https://www.raspberrypi.org/documentation/remote-access/samba.md)<br>
[Stack Exchange refernce](https://raspberrypi.stackexchange.com/questions/40974/access-network-samba-share-from-pi-client)<br>
[Link 1](https://www.juanmtech.com/samba-file-sharing-raspberry-pi/)<br>
[Video](https://www.youtube.com/watch?v=4P5nEH9zGDI)<br>
```
sudo apt-get update
sudo apt-get install samba samba-common-bin smbclient cifs-utils
```

### VPN Set up
[Video Setup](https://www.youtube.com/watch?v=WA7QTM9hovQ)<br>
[VPN Official Site](http://www.pivpn.io/)<br>


### Install Team Viewer
[Install TeamViewer](https://linuxize.com/post/how-to-install-teamviewer-on-ubuntu-18-04/)

### Install Adobe PDF Reader
```bash
sudo add-apt-repository "deb http://archive.canonical.com/ precise partner"
sudo apt-get update
sudo apt install adobereader-enu
https://askubuntu.com/questions/767937/how-do-i-install-adobe-acrobat-in-ubuntu-16-04
```
### KeyBoard Set up 
```
sudo dpkg-reconfigure locales # ==> Change from en_GB.UTF-8 to en_US.UTF-8.
sudo dpkg-reconfigure keyboard-configuration # ==> change the keyboard to USA PC104 
# You can also change these setting from Pref => Keyboard Setting => Advanced
```
[source](https://www.adafruit.com/product/1738)

### Interesting Project 
1. [Calender Dashboard](https://www.hanselman.com/blog/HowToBuildAWallMountedFamilyCalendarAndDashboardWithARaspberryPiAndCheapMonitor.aspx)
2. [Pi VPN : Secure and Private Home Network]()
3. [Pi Cluster : Computational Power]()
4. [Pi Cam : Live Streaming]()
5. [Pi Cloud : Media Server]()
6. [Pi Hub : Home Automation]()
7. [Pi Cluster : Using Kubernetes]()
8. [Pi Swarm : Docker Swarm]()
9. [Pi Forecast : Weather Report]
10. [Pi Bart Schedule](https://api.bart.gov/docs/overview/examples.aspx)
11. [Install Heroku Cli on Pi](https://gist.github.com/kogcyc/39087873a8e9a5370376a43020ce1603)
12. [IFTT](https://thepihut.com/blogs/raspberry-pi-tutorials/using-ifttt-with-the-raspberry-pi)
