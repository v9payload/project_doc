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

## Schritt 1

### Installing the extensions in Visual Studio Code


#### Overview of the general extensions:

![grafik](https://user-images.githubusercontent.com/110160647/181711679-0a042d63-5f08-416c-abb7-1e315ed0778d.png)

<br>

Um diese Erweiterungen zu installieren, müssen Sie links in der Navigation unter "Extensions" navigieren.<br> Geben Sie danach die Namen der Erweiterungen ein.
<br>

![extensions](https://user-images.githubusercontent.com/110160647/184134307-23f6b4a3-8f61-4efe-b746-3c0d5237b88a.PNG)

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


Um auf den Server zugreifen zu können, müssen wir den Host erstmal in einer Config abspeichern. Das erbringt uns den Vorteil, später schneller wieder auf den Server zugreifen zu können.
<br>

![add_host_conf](https://user-images.githubusercontent.com/110160647/182157731-62c93e6e-900c-4f72-8d8d-c5189bbd21fa.png)

* Wählen sie \\.ssh\config aus und speichern Sie dort den Host ab

<br>

## Schritt 4
Zu diesem Zeitpunkt können wir nun auf den Server zugreifen und beliebige Ordner öffnen. Um dies zu machen folgen Sie den folgenden Anweisungen.
<br>

![connect_host](https://user-images.githubusercontent.com/110160647/182360683-3950f01a-e740-4c46-96ea-36d1e458aa18.png)

* Drücken Sie erneut F1 um die Kommandozeile zu öffnen
* Geben Sie nun **"Connect to Host"** ein, um sie Serverliste anzeigen zu lassen
* Wählen Sie jetzt ihren hinzugefügten Server aus und bestätigen Sie mit Enter
* Geben Sie dann ihr Passwort ein und verbinden Sie sich mit dem Server

Um sicher zu gehen das Sie mit dem Server verbunden sind, sehen Sie unten links in der Ecke.
<br>
![grafik](https://user-images.githubusercontent.com/110160647/184135041-3deaa4d7-3151-4f6b-9a45-a26df91f3754.png)

## Schritt 5
Sie werden dann auf die "Startseite" kommen und sehen dieses Bild
<br>

![new_folder](https://user-images.githubusercontent.com/110160647/182362464-a3c6ba15-925f-4a0b-923f-c29fdd26a69b.png)

* Wählen Sie **"Open Folder"**

![folder_selec](https://user-images.githubusercontent.com/110160647/183591156-10d14d27-272e-42f5-a5a3-cc68290457c9.png)

* Nun können Sie einen beliebigen Ordner auf Ihrem Server auswählen und hinzufügen
* Um das Terminal zu öffnen navigiren Sie oben in der Bar auf Terminal

![terminal](https://user-images.githubusercontent.com/110160647/182362904-e3a93f2b-995b-49fd-b606-a66c8b36c318.png)
