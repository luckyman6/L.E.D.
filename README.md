<h1 align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&width=435&lines=%22LED%22+-+Lucky+Exfiltration+Data+😈" alt="Typing SVG" /></a>
</h1>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#Description">Description</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#Contributing">Contributing</a></li>
    <li><a href="#Version-History">Version History</a></li>
    <li><a href="#Acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

# L.E.D - "Lucky Exfiltration Data"

A payload to exfiltrate browsers history files and upload them into the attacker Dropbox Folder.

## Description

Since the primary payload only starts a WIN + R console which will override the security execution commands prevention in Powershell, you will have to upload the file named LED.ps1 to your dropbox, and insert the link in the payload.txt file properly as the payload indicates.

After the command is executed and the LED.ps1 script launches, the files in the Directories listed in LED.ps1 will be uploaded automatically to your Dropbox Folder.
(Attention: You must have a developer account in Dropbox which allow you to insert the uploading token to the API folder where the exfiltrated files will be uploaded.
You can find information on this easily online.)

## Getting Started

### Dependencies

* DropBox or other file sharing service - Your Shared link for the intended file
* Windows 10,11

<p align="right">(<a href="#top">back to top</a>)</p>

### Executing program

* Modify LED.ps1 file with your API Accces Token from Dropbox so your exfiltrated files are uploaded.
* Modify 'payload.txt' file with your download link for your modified LED.ps1 file from Dropbox.
* Use Duckyencoder.jar to encode the 'payload.txt' file into an 'inject.bin' USB Rubber Ducky can execute.
  Note: If you prefer, you can use new HAK5 PayloadStudio Community Edition to encode the payload.txt file. <a href="https://payloadstudio.com/community/">LINK</a>
* Insert inject.bin file into your SD card.
* Place SD Card into your Rubber-Ducky, sit back and watch!

<p align="right">(<a href="#top">back to top</a>)</p>

## Contributing

luckyman6

<p align="right">(<a href="#top">back to top</a>)</p>

## Version History

* 0.1
    * Initial Release

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Hak5](https://hak5.org/)
* [Official-Repository-Payloads](https://github.com/hak5/usbrubberducky-payloads)

<p align="right">(<a href="#top">back to top</a>)</p>
