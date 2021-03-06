## Powershell Terminal built with Node.js
This is a web-based terminal / script runner for powershell.  It is built in Node.js. As a result, if Powershell is installed on a Linux or macOS device, this app should work.

Creating a web-based powershell terminal enables you to remotely run powershell through your web browser.  While this introduces tons of security concerns, I think it is a powerful concept that is worth considering.

My implementation is very basic, there is no security, so I would only run it within your network.

It consists of a editor pane and an output pane, like Powershell ISE.  Press ctrl+space for autocomplete.

To try it out, clone the project:

`git clone https://github.com/JacFearsome/powershell-terminal-nodejs.git`

Install the node module dependencies:
	
`cd powershell-terminal-nodejs && npm install`

Run the app:

`node server.js`

And finally, go to http://localhost:7878/ in your web browser.

Screenshot:
![alt text](https://www.jesserussell.net/wp-content/uploads/2017/11/powershell-terminal-nodejs3.png)
