# Documentation about SSH sessions and Terraform in Visual Studio Code

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

## Schritt 1

### Installing the extensions in Visual Studio Code


#### Overview of the general extensions:

![grafik](https://user-images.githubusercontent.com/110160647/181711679-0a042d63-5f08-416c-abb7-1e315ed0778d.png)

<br>

Um diese Erweiterungen zu installieren, müssen Sie links in der Navigation unter "Extensions" navigieren.<br> Geben Sie danach die Namen der Erweiterungen ein.
<br>

>#### **Extensions > "Search Extensions in Marketplace"**
<br>

Nachdem Sie die Erweiterungen installiert haben, können wir nun mit dem verbinden des Servers fortfahren.
<br>

![f1_vsc](https://user-images.githubusercontent.com/110160647/182132040-ee7c8061-ba04-438d-862a-d71f20d06609.png)

* Drücken Sie F1, um in die Kommandozeile zu kommen
* Geben sie danach **"add new Host"** ein

<br>

## Schritt 2
Hinzufügen des Servers in der *conf* Datei
<br>

![add_host](https://user-images.githubusercontent.com/110160647/182156682-30782771-19f9-4da2-a680-d07ba3144bfd.png)

* Geben Sie nun einen Server ein **"ssh user@ihrServer"**

<br>

## Schritt 3
![add_host_conf](https://user-images.githubusercontent.com/110160647/182157731-62c93e6e-900c-4f72-8d8d-c5189bbd21fa.png)

* Wählen sie \\.ssh\config aus und speichern Sie dort den Host ab
