# Floorp-GNOME-Theme
Bridges support from Firefox-gnome-theme

## Repos Used:  
* [WhiteSur-gtk-theme](https://github.com/vinceliuice/WhiteSur-gtk-theme) or [WhiteSur-Firefox-theme](https://github.com/vinceliuice/WhiteSur-firefox-theme)
* [Firefox-Gnome-Theme](https://github.com/rafaelmardojai/firefox-gnome-theme)
* [Floorp Browser](https://github.com/Floorp-Projects/Floorp)

All Code used is from their respective repos. I have not changed anything.

## Output:  

![image](https://github.com/SVTA-OP/GNOME-Theme/assets/126323835/eba455e1-a6e1-41f7-84a3-18fd9c7bb7c0)

## Tutorial:  

  * Go ahead and install the firefox gnome theme with any method, like the curl install or manually.
  * Open Floorp and head to `about:support`.
  * Locate the Profile Directory and open it. Do the same for firefox.
  * Copy over all of the contents from firefox's chrome folder and onto floorp.
  * Now download a zip or clone the WhiteSure-firefox-theme repo.
  * Open up a terminal in that repo and type `install.sh -e`. (Steps may change with the WhiteSur-gtk-theme repo)
  * In the nano editor that pops up, open the location that is seen in the top of the editor.
  * Copy `Userchrome.css` and the `WhiteSur` folder into floorp's chrome folder. Make sure that the firefox-gnome-theme directory is still there.
  * Open `Userchrome.css` (assuming you overwrote the file) and add `@import "firefox-gnome-theme/userChrome.css";`.
  * Remember to take line 6 and comment it, `/*@import "WhiteSur/theme.css"; /**/`
  * Now you can go through the file and uncomment whatever option you would like.
  * Close the file and restart floorp.

