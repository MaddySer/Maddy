## Thanks for Everything
### We will always remember you..

<div align="center">
  <img border-radius: 15px src="maddy.jpg" width="200" height="200"/>
  <p align="center">
<a href="#"><img title="HolyMaddy" src="https://img.shields.io/badge/HOLYMADDY-pink?colorA=%23ff0000&colorB=%23017e40&style=for-the-badge"></a>
</p>
  <p align="center">
<a href="http://Wa.me/299556666"><img title="join support" src="https://img.shields.io/badge/join_support-MaddySer/HolyMaddy?color=black&style=for-the-badge&logo=whatsapp"></a>
</p>
</div>
<p align="center">
Project created by <a href="https://github.com/MaddySer">Maddy</a> to make it public
    <br>
       | © |
        Reserved |
    <br> 
</p>


----

  <p align="center">
  <a href="https://github.com/MaddySer/Maddy ">
    <img src="https://img.shields.io/github/repo-size/MaddySer/lastpink?color=green&label=Repo%20total%20size&style=plastic">
<p align="center">
<a href="https://github.com/MaddySer/followers"><img title="Followers" src="https://img.shields.io/github/followers/MaddySer?color=red&style=flat-circle"></a>
<a href="https://github.com/MaddySer/lastpink/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/MaddySer/lastpink?color=red&style=flat-square"></a>
<a href="https://github.com/MaddySer/lastpink/network/members"><img title="Forks" src="https://img.shields.io/github/forks/MaddySer/lastpink?color=red&style=flat-square"></a>
<a href="https://github.com/MaddySer/lastpink/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/MaddySer/lastpink?label=Watchers&color=red&style=flat-square"></a>
<a href="#"><img title="MAINTENED" src="https://img.shields.io/badge/UNMAINTENED-YES-blue.svg"</a>

```
  
Maddy - Maddy Userbot is Open Source software open to development. 
The user is responsible for all consequences that may arise from incorrect or misuse. 
Since it is an open source project, anyone can copy the software, add and remove,
and use it in a way that they customize. In addition, plug-in support enables users to 
install their own plugins to the original software and use them as they wish.
Using the bot out of purpose will explicitly ban you.
Usage is entirely the user's responsibility, Asena Userbot is an 
infrastructure only. Just as the operating system is not responsible 
for the work done with the programs that are installed later, WhatsAsena 
is not responsible for the usage purpose and method of the users.
Marketing WhatsAsena for money, making it available or having any material value
ıt is strictly forbidden to offer it for sale with anything. All legal investigations that may arise
the user is responsible.
```


## Setup
<div align="center">

  ### Simple Method
  
[![Run on Repl.it](https://repl.it/badge/github/quiec/whatsAlfa)](https://replit.com/@MaddySer/Maddy-QR)
 
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://github.com/MaddySer/Maddy) 
  
  [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/MaddySer/Maddy) 
 
  </div>
 
<br>
<br >
If Repl.it not working Try Termux for Qr scanning.Just Copy the Link Below in Termux
```
bash <(curl -L https://t.ly/tHxh)
``` 

            
### NO ERROR DEPLOY
            
```
  for easy deploy fork this repo & add the given link in your readme by changing repository link - [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=your repository link here)
```
## F.A.Q
Answer a few frequently asked questions;
### Can you read my messages?
This project is open source so all the codes are clear. Neither less nor more; you can look what you want. **We absolutely do not have access to your accounts.**

### What about our security?
If you are concerned about security, you can install it on your own computer. If you think someone else has captured your data, simply click on **Whatsapp> Three Dots> Whatsapp Web> Logout** from all sessions button.

### Is it paid?
**Of course not.** It will never happen. But you can donate to us. You can reach me via [Telegram](https://t.me/maddy) .

### ⚠️ Warning! 
```
Due to Userbot; Your WhatsApp account may be banned.
This is an open source project, you are responsible for everything you do. 
Absolutely, Asena executives do not accept responsibility.
By establishing the Asena, you are deemed to have accepted these responsibilities.
```


## License
This project is protected by `GNU General Public Licence v3.0` license.

### Disclaimer
`WhatsApp` name, its variations and the logo are registered trademarks of Facebook. We have nothing to do with the registered trademark
  
### thanks for your help and support guys
    `ic brothers`

### when forking  
```
add your own heroku button
  
  example :
  [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=your repository link here)
  
  change it into your repo link
```
  
```
 If you want add bgm (voice auto reply),sticker (auto reply)

 create 3 files name them bgmone,bgmtwo,stick
 upload your mp3/sticker to created folder

 open plugins/filter.js , change path    
     for bgm one 
        change line 133 in filter.js to 

          await message.client.sendMessage(message.jid, fs.readFileSync('./bgmone/' + a + '.mp3'), MessageType.audio, { mimetype: Mimetype.mp4Audio, quoted: message.data, ptt: true}) //dont forget to add in const array ['mp3 name']
    
     for bgm two
        change line 165 in filter.js into

          await message.client.sendMessage(message.jid, fs.readFileSync('./bgmtwo/' + a + '.mp3'), MessageType.audio, { mimetype: Mimetype.mp4Audio, quoted: message.data, ptt: true})  //dont forget to add in const array ['mp3 name']

    for sticker
        change line 193 in filter.js

          await message.client.sendMessage(message.jid, fs.readFileSync('./stick/' + a + '.mp3'), MessageType.audio, { mimetype: Mimetype.mp4Audio, quoted: message.data, ptt: true})  //dont forget to add in const array ['sticker name']
```
