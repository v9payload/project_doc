# Documentation about SSH sessions in Visual Studio Code

This documentation is about what extensions you need to create and edit files live in an SSH session.
It also shows how to get Terraform code directly into the folders on the respective server.

<br>

## Extensions you need
* Remote - Containers
* Remote - SSH
* Remote - SSH: Editing Configuration Files
* Remote - WSL
* Remote Development

<br>

## Step 1

### Installing the extensions in Visual Studio Code


#### Overview of the general extensions:

![grafik](https://user-images.githubusercontent.com/110160647/181711679-0a042d63-5f08-416c-abb7-1e315ed0778d.png)

<br>

To install these extensions, you need to navigate to the left in the navigation under "Extensions".<br> Then enter the names of the extensions.
<br>

![extensions](https://user-images.githubusercontent.com/110160647/184134307-23f6b4a3-8f61-4efe-b746-3c0d5237b88a.PNG)

>#### **Extensions > "Search Extensions in Marketplace"**
<br>

## Step 2

After you have installed the extensions, we can now proceed with connecting the server.
<br>

![f1_vsc](https://user-images.githubusercontent.com/110160647/182132040-ee7c8061-ba04-438d-862a-d71f20d06609.png)

* Press F1 to enter the command line
* After that enter **"add new Host "**

<br>

## Step 3
Adding the server in the *conf* file
<br>

![add_host](https://user-images.githubusercontent.com/110160647/182156682-30782771-19f9-4da2-a680-d07ba3144bfd.png)

* Now enter a server **"ssh user@exampleServer"**

<br>


To access the server, we must first save the host in a config file. This gives us the advantage of being able to access the server again more quickly later.
<br>

![add_host_conf](https://user-images.githubusercontent.com/110160647/182157731-62c93e6e-900c-4f72-8d8d-c5189bbd21fa.png)

* Select \\.ssh\config and save the host there

<br>

## Step 4
At this point we can now access the server and open any folders. To do this, follow the instructions below.
<br>

![connect_host](https://user-images.githubusercontent.com/110160647/182360683-3950f01a-e740-4c46-96ea-36d1e458aa18.png)

* Press F1 again to open the command line
* Now enter **"Connect to Host "** to display the server list.
* Now select your server and confirm with Enter
* Then enter your password and connect to the server

To make sure you are connected to the server, look in the bottom left corner.
<br>
![grafik](https://user-images.githubusercontent.com/110160647/184135041-3deaa4d7-3151-4f6b-9a45-a26df91f3754.png)

## Step 5
You will come to the "Homepage" and see this image
<br>

![new_folder](https://user-images.githubusercontent.com/110160647/182362464-a3c6ba15-925f-4a0b-923f-c29fdd26a69b.png)

* Select **"Open Folder"**

![folder_selec](https://user-images.githubusercontent.com/110160647/183591156-10d14d27-272e-42f5-a5a3-cc68290457c9.png)

* Now you can select and add any folder on your server
* To open the terminal, navigate to Terminal at the top of the bar.

![terminal](https://user-images.githubusercontent.com/110160647/182362904-e3a93f2b-995b-49fd-b606-a66c8b36c318.png)
