# relai
Relai IRC client for Firefox OS

This app is currently non functional and is only the main chat UI.

#Connection UI

![alt tag](http://i.imgur.com/NtFy48m.png)

#Chat UI

![alt tag](http://i.imgur.com/qCj2kWm.png)

#Compile instructions

Relai uses SCSS as a CSS preproccessor. You must install SASS to generate the CSS file.
Follow instructions on http://sass-lang.com/install to install SASS on your machine.

Once SASS has been installed on your machine, run this command from your command line

sass --update style.scss:style.css

The above command will compile the SCSS file into a usable CSS file. Once SCSS has been
compiled into CSS, you can install Relai on your Firefox OS device.