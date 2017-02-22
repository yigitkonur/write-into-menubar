# Write Text into Menubar (BitBar + Alfred)

Do you deal with tens of different tasks in a hour and end up with forgetting what you do 10 seconds ago? No prob! 

![alt tag][1]([http://url/to/img.png][2])

You can write a text string to remember which will stick into your menubar - so that you can remember what you were going to do. Just install BitBar + Alfred Powerpack and start to use.

### Installation

 * Make sure that you have a BitBar extension.
 * You BitBar plugin folder have to be installed \~/Documents/Bitbar-Plugins/
 * Drag and drop your BitBar plugin into \~/Documents/Bitbar-Plugins/write-into-menubar-bitbar-plugin.1s.sh
 * You need to run this Terminal Command to add chmod into your Bitbar Plugin
	  
```bash
chmod +x ~/Documents/Bitbar-Plugins/write-into-menubar-bitbar-plugin.1s.sh
```
 
### Customization
 
 You can also config this plugin according to you needs - just change variables in BitBar plugin:
 
 * You can change text color by changing: quote\_color="black"
 * You can set length of string by changing: max\_chars="30" 


### Dependencies

You need to have BitBar (completely free) and Alfred Powerpack (paid one) to use this plugin.

Take a look to download then:

 * [Alfred 3][3] to run .AlfredWorkflow
 * [BitBar][4] to show final result of .sh plugin


This plugin is made by [Yiğit Konur][5] for my daily routine at [Zeo][6]. If you need to get a support - please open an issue.




_Special thanks for [Jan Groß][7] to inspire me by his "Daily Quote" plugin to create my own._

[1]:	https://cldup.com/ZI7tiDY5Yf-2000x2000.jpeg "Better way to understand how it works"
[2]:	https://github.com/yigitkonur/write-into-menubar
[3]:	https://www.alfredapp.com/
[4]:	https://getbitbar.com/
[5]:	https://github.com/yigitkonur
[6]:	https://zeo.org
[7]:	https://getbitbar.com/contributors/JanGross