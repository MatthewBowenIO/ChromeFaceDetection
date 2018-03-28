# ChromeFaceDetection
Implementation of the Google Chrome Shapes Detection API for facial recognition on webcam feed.

# Use
The Shape Detection API in Chrome is currently in the 'experimental' phase and requires you to enable the 'Expirimental Web Platform features' flag. 
To do so go to: chrome://flags/#enable-experimental-web-platform-features

Accessing the webcam requires your connection to be HTTPS. For this project I run a python SimpleHTTPServer in the directory of index.html, then an ngrok instance pointed at that port. 

Python SimpleHTTPServer:
	// Default port is 8000
	python -m SimpleHTTPServer <port> 

Ngrok <https://ngrok.com/>: 
	./ngrok http <port>
