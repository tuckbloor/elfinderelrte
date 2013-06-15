elfinderelrte
=============

elfinder and elrte working to uploads folder

this is a combination of elfinder (file manager) and elrte (rich text editor) 

to select images on the server select the image icon and in the pop up where it says Image URL there is an image of a folder, click on that image and browse the server for files

configeration is 2 files inside the php directory there is a file called connecttor.php inside there edit where the images will be uploaded

line 34 the path

			'path'          => '../uploads/',         // path to files (REQUIRED) **************************** edit here **********************
			
and line 45 the url

             'URL'           => '/uploads/', // URL to files (REQUIRED)  **************************** edit here **********************
             
and inside index.html

line 43

 url : '/php/connector.php',//change root here