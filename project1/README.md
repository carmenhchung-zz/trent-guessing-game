# Coder Academy - Project 1 (Week 2)

The dev team consisted of Olivia (moiscraycray), Carmen (carmenhchung), James (J1marotta) and Nathan (nathankwon). Our mandate was to code a program using Ruby that would impress our teacher, Trent.


## Note to Windows users

Unfortunately, this program will only run on Apple Macs. Our team have tried to get it working on PCs but the gem, catpix, and associated gems are very difficult (if not impossible) to install.


## Motivation

We were asked to build something that would excite, entertain, and surprise the user (in this case, Trent). We decided the best approach would be to examine his social media accounts (predominantly his Facebook and Instagram) to discover what he was interested in. 

We quickly found that he has a lot of selfies, so our team decided to build a game around them. 

Our game is called: "Trent or Not?"


## Synopsis

The program is a game where players will guess whether the printed image is Trent (our teacher) or not. The game will track and tally the score at the end of the game.


## Installation

 You will need catpix and artii gems installed.
 Catpix, has additional requirements of tco and rmagic gems.
 Rmagic has the additional requirement of version 6 of image magick.


 Additionally you will need to save the files into home/user/sites/project1 - 
 including the trent and not trent directory folders so that the program can correctly find the pictures it uses. 
 These can be found here: https://drive.google.com/drive/folders/0B4E-nX-9D2HIeEQ5VnVaZmlPTXM?usp=sharing
 
 Installation for the catpix gem:
 
1. Uninstall Image Magick 7 (if exists since it conflicts) using homebrew
2. brew uninstall imagemagick && brew unlink imagemagick --force
3. Install Image Magick (version ImageMagick 6.9.9-5)
4. brew install imagemagick@6 && brew link --force imagemagick@6
5. Check relinking occurred after migration using Migration Assistant on macOS (i.e. not pkg-config: command not found)
6. Wand-config --ldflags --libs
7. Reinstall pkg-config http://www.rubydoc.info/gems/rmagick/frames#install
8. brew uninstall pkg-config
9. brew install pkg-config
10. brew unlink pkg-config
11. brew link pkg-config
12. Fix if error occurs Can't find MagickWand.h with:
    * Solution: Find library mdfind MagickWand.h
13. Install RMagick gem (v2.16.0)
14. gem install rmagick -v 2.16.0   
15. Install Catpix gem
16. gem install catpix -v 0.2.0

You should have: 
* version 6.9.9-5 of image magick;
* version 2.16 of rmagic; and
* version 0.2.0 of catpix. 

 
  Full documentation of our development process can be found here:
  https://docs.google.com/document/d/123UQIlLSAlehvuABBJSGmpdgEViTzfsWpxLudG543xY/edit?usp=sharing
"# Trent-or-Not-Game" 
"# Trent-or-Not-Game" 
