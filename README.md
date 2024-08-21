<<<<<<< HEAD
#  Customized NetworkSpeedtest with **[SpeedTest by OpenSpeedTest™](https://openspeedtest.com?Run&ref=Github)** - Free & Open-Source HTML5 Network Performance Estimation Tool.
=======
# Customized Network Speedtest based on **[SpeedTest by OpenSpeedTest™](https://openspeedtest.com?Run&ref=Github)** - Free & Open-Source HTML5 Network Performance Estimation Tool.
>>>>>>> 99848481478deb12307cca0bcc58fb518c4859eb

  

SpeedTest by OpenSpeedTest™ is a Free and Open-Source HTML5 Network Performance Estimation Tool Written in Vanilla Javascript and only uses built-in Web APIs like `XMLHttpRequest` `(XHR)`, `HTML`, `CSS`, `JS`, & `SVG`. No Third-Party frameworks or libraries are Required. All we need is a static web server like `NGINX`. I started this project in 2011 and moved to OpenSpeedTest.com dedicated Project/Domain Name in 2013.
  

###  Secure by Design.

  

OpenSpeedTest contains Only `STATIC` Files like `HTML`,`CSS` & `JS`.

So you don't need to worry about Security Updates or Hidden Exploits that may compromise your secure environments.

  

###  Lightweight, High Performance.

  

OpenSpeedTest is written in Vanilla JavaScript. No Third-Party frameworks or libraries were used. SpeedTest script file size is under 8kB gzip. The unexpected side effect of using Vanilla JavaScript is High Performance.

  

###  Run a speed test from Any Device.

  

OpenSpeedTest will run on Any Web Browser that is IE10 or newer.

  

###  Ready for Any Display Size and Resolution.

  

OpenSpeedTest User interface is written in SVG.

  

#  Create Your Own SpeedTest Server.

###  Server Requirements :

`Nginx`, `Apache`, `IIS`, `Express`, or Any Web server that supports `HTTP/1.1` or newer.

- Accept, `GET`, `POST`, `HEAD` & `OPTIONS`, Response `200 OK`.

- Accept, `POST` to Static Files, Response `200 OK`.

- `client_max_body_size`, 35 Megabytes or more.

- Timeout greater than `60 seconds`.

- Disable `Access logs` for Increasing server performance.

- Improve `Time to First Byte` (TTFB)

- Warning! If you run it behind a **[Reverse Proxy](https://github.com/openspeedtest/Speed-Test/issues/4#issuecomment-1229157193)**, you should increase the `post-body content length` to 35 megabytes.
- Supports `HTTP2` & `HTTP3`.
- `HTTP1.1` is recommended for achieving maximum performance.
- **[You Should Follow our Nginx Config.](https://github.com/openspeedtest/Nginx-Configuration)**

  

#  Or, You can use OpenSpeedTest-Server.

OpenSpeedTest-Server is available for  Windows, Mac, Linux, Android, iOS & Docker. 

