# Supercollider package for Sublime Text 2

Tested on Windows XP only at the moment.  
Feel free to test it on other environments, fork and pull.  

The syntax highlighting comes from RFWatson's SuperCollider TM Bundle  
https://github.com/rfwatson/supercollider-tmbundle

Sublime Text 2 home page  
http://www.sublimetext.com/2

Supercollider home page  
http://supercollider.sourceforge.net

## Usage
- Open Sublime Text 2  
- Go to Preferences/Browse Packages  
- Create a SuperCollider directory.  
- Copy and paste all the files from this repository in it.  
- Change Supercollider path in SuperCollider.sublime-settings
- Restart Sublime Text 2  
- In Tools, there is a new Supercollider sub menu which allows you to :
  - start and stop sclang, 
  - evaluate a line (ctrl+enter), 
  - stop all sounds (ctrl+.), 
  - search word in SCCode.org,
  - and show/hide the console.  
- If your line starts with the character '(', it should evaluate the whole expression.  

## Known bugs
- on Windows XP
  
  Server.local.boot;

does not work.
You should use 

  Server.default = s = Server.internal;
  s.boot;

instead.

## Authors
[Geoffroy Montel](http://github.com/geoffroy.montel)
[RFWatson](https://github.com/rfwatson)