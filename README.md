
# **How to set up Windows Subsystem for Linux (WSL)?** <br />


<br />


### **AUTHOR: Dr Asad Prodhan** https://asadprodhan.github.io/


<br />


## **Step 1: Activate WSL in your Windows Laptop**
 

- Type "Windows features" into the search bar located in your compupter taskbar 


- Expand the "Turn Windows Features On or Off" box and tick the checkbox for "Windows Subsystem for Linux" 


> Ref: https://techcommunity.microsoft.com/t5/windows-11/how-to-install-the-linux-windows-subsystem-in-windows-11/m-p/2701207/page/2


<br />


## **Step 2: Download Ubuntu 18.04 LTS via the Microsoft Store**


- Visit the following Microsoft store link: 


> https://apps.microsoft.com/detail/9pnksf5zn4sw?hl=en-us&gl=AU


- Download Ubuntu 18.04 LTS


<br />


## **Step 3: Set up your Linux username and password**


- Once downloaded, open the Ubuntu terminal by searching it into the search bar located in your compupter taskbar


- It will prompt you to set up your username and password


Ubuntu only accepts usernames based on the following rules:

- Must start with a lowercase letter

- May only contain lowercase letters, underscore (_), and dash (-)

- May optionally end with a dollar sign ($)


> Ref: https://learn.microsoft.com/en-us/windows/wsl/setup/environment#set-up-your-linux-user-info


Note: Downloading Ubuntu 18.04 LTS for Windows from the Microsoft store, should automatically install WSL. If not, then:

Run the following command in the Ubuntu terminal

```
wsl --install
```


<br />


## **Step 4: Install MobaXterm**


MobaXterm is a terminal application for Windows computers. 


With MobaXterm, you can connect to a remote computer using SSH connection. It has a sftp window that allows for a drag-and-drop option for transferring file between remote and local computers 


- Visit the MobaXterm (https://mobaxterm.mobatek.net/)


- Download the Home Edition version (https://mobaxterm.mobatek.net/download.html) 


<br />


## **Step 5: Update and upgrade packages**


- Regularly update and upgrade your Linux packages


- Run the following command


```
sudo apt update && sudo apt upgrade
```


You can install differents pacakges as you go. 
For example:


You can install the widely used Linux utility, dos2unix, by running the following command in your   

```
sudo apt-get install dos2unix
```


```
sudo apt-get install zip
```

