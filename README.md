<img src="https://cdn.discordapp.com/attachments/606095551192236045/641789222457573378/IMG_C64D2A0ECC34-1.jpeg" alt="preview" width="200" height="360">

###### Screenshot by fahrenheight#0001
#### This project was made for the iOS Jailbreaking server (https://discord.gg/3Xqqn4a) but is distributed under the MIT Public License so you can change the contents or make your own theme from this as a base.

# Installing
A. download a deb at https://github.com/edog813/shitos/releases
B.
# Contribution Requirements
Please make the icon a png that is 1000x1000. the icon should be as close to the normal icon as possible unless the icon is bad. If it's something like Youtube or Reddit where its a small glyph please fix it to actually be good where the background isnt white.

after you do that here's how you contribute

1. go to https://offcornerdev.com/bundleid.html
2. copy the bundleid of your app
3. make the icon name com.bundle.id.png
4. make a pull request

sorry that half the original icons dont fit this specification I blame edog813

# Build Instructions
First you will need a computer/virtual machine with dpkg installed. Any computer that has dpkg-deb will work and if you use a distro that isn't debian/ubuntu-like you can just install dpkg with your package manager or build it from source.

`cd /tmp`\
`git clone https://github.com/edog813/ShitOS`\
`dpkg-deb -b ShitOS/ $HOME/shitos_iphoneos-arm_master.deb`

this will put a deb in your home folder

# Credits
icon design, idea -- Edog813#9023\
git repo, instructions, deb -- Human#1895\
Testing - Fahrenheight#0001
