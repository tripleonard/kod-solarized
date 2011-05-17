Solarized style for the Kod editor
==================================
  
Developed by [Trip Leonard](http://trip.invisibledog.net)
  
This is a "solarized" style for the Kod editor (http://kodapp.com). 
The palette was developed by Ethan Schoonover 
(http://ethanschoonover.com/solarized)*.
Installation
============
  
Copy the file to ~/.kod/mystyle_solarized.css then tell Kod where to find it
by setting a configuration key:
 
    $ defaults write se.hunch.kod style/url ~/.kod/mystyle_solarized.css

You might need to restart Kod for changes to take effect or 
select View->Reload style from the menu. Then, simply open
your ~/.kod/mystyle.css in Kod -- when edited and saved Kod will
automatically reload the style, thus you see the effect of your 
alterations.

Usage
=====

Currently there is one .css file with the light commented out.
When you want to switch just comment out the dark, 
uncomment the light and save, Kod auto reloads when 
it notices that the file you just saved is the Kod CSS file.  
  
Screen shots
===
CSS Dark
---
![css dark](https://github.com/tripleonard/kod-solarized/raw/master/img/kod-css-dark.png)

CSS Light
---
![css light](https://github.com/tripleonard/kod-solarized/raw/master/img/kod-css-light.png)
SQL Dark
---
![sql dark](https://github.com/tripleonard/kod-solarized/raw/master/img/kod-sql-dark.png)
SQL Light
---
![sql light](https://github.com/tripleonard/kod-solarized/raw/master/img/kod-sql-light.png)

*Colors used:
    SOLARIZED HEX     
    --------- ------- 
    base03    #002b36  8/4 brblack  
    base02    #073642  0/4 black    
    base01    #586e75 10/7 brgreen  
    base00    #657b83 11/7 bryellow 
    base0     #839496 12/6 brblue   
    base1     #93a1a1 14/4 brcyan   
    base2     #eee8d5  7/7 white
    base3     #fdf6e3 15/7 brwhite
    yellow    #b58900  3/3 yellow 
    orange    #cb4b16  9/3 brred
    red       #d30102  1/1 red
    magenta   #d33682  5/5 magenta
    violet    #6c71c4 13/5 brmagenta
    blue      #268bd2  4/4 blue
    cyan      #2aa198  6/6 cyan
    green     #859900  2/2 green
