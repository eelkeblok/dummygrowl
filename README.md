dummygrowl
==========
This is a display style for Growl - the Mac OS X notification system - that 
doesn't display anything. This is useful if you have Growl display notifications 
in a different way, such as Bark.

With the recent update to Growl 2.0, the excellent [Bark](http://barkplug.in) 
was turned into an action plugin. This leaves "regular" Growl notifications 
alone and functional.

Although it is unclear at this point whether this is a bug or a feature, setting
Growl to "No default display" does not disable regular Growl notifications. 

Enter Dummy.growlStyle. This is a very barebones Growl display plugin, that 
simply doesn't display any notifications. Let Bark handle Growl notifications 
through Mountain Lion Notification Center, and don't be bothered by standard 
Growl notifications.

Installation
------------
To allow for easy access while developing, the content of the plugin package is 
not placed in a package that has a name recognized by Growl. To get a package, 
run the build.sh script from the terminal. 

    $ cd ~/Downloads
    $ unzip dummygrowl.zip
    $ cd dummygrowl
    $ ./build.sh

Now, navigate to Downloads/dummygrowl and double click Dummy.growlStyle. Growl 
will report it has installed the plugin and ask you whether you want to 
configure it. Respond yes, and select "Dummy" as the default display style (the 
configuration controls displayed for the Dummy style are obviously not 
functional, because the purpose of the plugin is to *not* display anything. If 
anybody knows how to get rid of the controls, please let me know or submit a pull 
request).
