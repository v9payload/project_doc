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

## Schritt 2

Nachdem Sie die Erweiterungen installiert haben, können wir nun mit dem verbinden des Servers fortfahren.
<br>

![f1_vsc](https://user-images.githubusercontent.com/110160647/182132040-ee7c8061-ba04-438d-862a-d71f20d06609.png)

* Drücken Sie F1, um in die Kommandozeile zu kommen
* Geben sie danach **"add new Host"** ein

<br>

## Schritt 3
Hinzufügen des Servers in der *conf* Datei
<br>

![add_host](https://user-images.githubusercontent.com/110160647/182156682-30782771-19f9-4da2-a680-d07ba3144bfd.png)

* Geben Sie nun einen Server ein **"ssh user@exampleServer"**

<br>

## Schritt 4
Um auf den Server zugreifen zu können, müssen wir den Host erstmal in einer Config abspeichern. Das erbringt uns den Vorteil, später schneller wieder auf den Server zugreifen zu können.
<br>

![add_host_conf](https://user-images.githubusercontent.com/110160647/182157731-62c93e6e-900c-4f72-8d8d-c5189bbd21fa.png)

* Wählen sie \\.ssh\config aus und speichern Sie dort den Host ab

<br>

## Schritt 5
Zu diesem Zeitpunkt können wir nun auf den Server zugreifen und beliebige Ordner öffnen. Um dies zu machen folgen Sie den folgenden Anweisungen.
<br>

![connect_host](https://user-images.githubusercontent.com/110160647/182360683-3950f01a-e740-4c46-96ea-36d1e458aa18.png)

* Wählen Sie jetzt ihren hinzugefügten Server aus und bestätigen Sie mit Enter
* Geben Sie dann ihr Passwort ein und verbinden Sie sich mit dem Server

## Schritt 6
Sie werden dann auf die "Startseite" kommen und sehen dieses Bild
<br>

![new_folder](https://user-images.githubusercontent.com/110160647/182362464-a3c6ba15-925f-4a0b-923f-c29fdd26a69b.png)

* Wählen Sie **"Open Folder"**

![folder_selec](https://user-images.githubusercontent.com/110160647/182362631-e8874e44-9812-4a36-b83c-5ba1c2f5dc7a.png)
