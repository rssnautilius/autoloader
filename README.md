# autoloader
This script loads a text file  in a html page and updates it every few seconds 

Write file.txt with a 3rd party software every few seconds 

operation mode 1  
use song.html to look at the latest form of the file in a slightly stiled mode (this can be runed as a stand alone not include in a web server ) 
tested ok useful when feeding a realtime feed in a webpage or a twitch stream for example 
#to do find a way to truly style the text 


operation mode 2
use a url instead of file.txt and use autoloader.html to se ethe updated file in a standalone page 
ofc u can also use the autoloader.html directly on the server but in that case useing a php call like file_get_contents would probably be more efficient 
#todo testing 
