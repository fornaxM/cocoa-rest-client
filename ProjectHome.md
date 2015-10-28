# Moved to Github #
Website: http://mmattozzi.github.io/cocoa-rest-client/

Github project: http://github.com/mmattozzi/cocoa-rest-client

[Download Latest Release!](https://github.com/mmattozzi/cocoa-rest-client/releases)

**Moved since Google Code will no longer support releasing new binary downloads in 2014... Releases and source will be available on [Github](http://github.com/mmattozzi/cocoa-rest-client).**


---


# About #
CocoaRestClient is a Mac OS X app for testing HTTP/Restful endpoints.

I love curl, but sometimes I need my output XML or JSON pretty printed. I want to be able to save frequent PUT and POST bodies for later and copy and paste from responses easily. Think of this as curl with a light UI.

The goal of this project is to build a lightweight native Cocoa app for testing and debugging HTTP Restful services.
This project was greatly inspired by the Java rest-client (http://code.google.com/p/rest-client/).

## Features ##
  * Make GET, PUT, POST, DELETE, HEAD calls
  * Set request body to arbitrary content
  * Set request headers
  * Set HTTP basic & digest auth
  * Auto-format (pretty print) XML and JSON responses with syntax highlighting
  * Display response headers
  * Quick save requests in a handy drawer
  * Send multipart/form-data <sup>new in 1.1</sup>
  * Upload files via multipart/form-data <sup>new in 1.1</sup>
  * Enter POST/PUT input as raw input or key/value pairs <sup>new in 1.1</sup>
  * Reports response latency <sup>new in 1.2</sup>
  * Command-R reloads last request <sup>new in 1.2</sup>
  * Lightweight: Low real memory usage
  * Automatic updates <sup>new in 1.2.2</sup>
  * SSL Support
  * Optionally follows HTTP redirects
  * Go full screen in Lion <sup>new in 1.2.4</sup>
  * Import and export requests <sup>new in 1.3</sup>
  * Export responses to files, default browser, or application <sup>new in 1.3.3</sup>

## Screenshots ##

![http://cocoa-rest-client.googlecode.com/svn/trunk/screenshots/cocoa-rest-client-1.jpg](http://cocoa-rest-client.googlecode.com/svn/trunk/screenshots/cocoa-rest-client-1.jpg)

**Pretty print XML content. Quick save of request URLs, body, and headers in one convenient drawer.**

<br />

![http://cocoa-rest-client.googlecode.com/svn/trunk/screenshots/cocoa-rest-client-2.jpg](http://cocoa-rest-client.googlecode.com/svn/trunk/screenshots/cocoa-rest-client-2.jpg)

**Pretty print JSON content. Set and save HTTP headers.**

<br />

![http://cocoa-rest-client.googlecode.com/svn/trunk/screenshots/cocoa-rest-client-3.jpg](http://cocoa-rest-client.googlecode.com/svn/trunk/screenshots/cocoa-rest-client-3.jpg)

**Set HTTP Basic or Digest Auth. Displays HTTP response headers.**

<br />

![http://cocoa-rest-client.googlecode.com/svn/trunk/screenshots/cocoa-rest-client-4.jpg](http://cocoa-rest-client.googlecode.com/svn/trunk/screenshots/cocoa-rest-client-4.jpg)

**Set HTTP request body content to a raw text blob or a list of parameters.**

<br />

![http://cocoa-rest-client.googlecode.com/svn/trunk/screenshots/cocoa-rest-client-5.jpg](http://cocoa-rest-client.googlecode.com/svn/trunk/screenshots/cocoa-rest-client-5.jpg)

**Upload files using HTTP multipart requests. HTTP form encoding also supported.**

<br />

## Source and Contributions ##
  * Source code is now hosted on Github: http://github.com/mmattozzi/cocoa-rest-client
  * If you would like to contribute, please fork and create a pull request on Github
  * Downloads and issues will still be kept up to date on Google Code. I will probably keep source up to date with each release.
  * I don't plan on switching from Garbage Collection to ARC until I drop 10.6 support, as there seems to be some [limitations with ARC on 10.6](http://stackoverflow.com/questions/7696201/how-to-deploy-to-snow-leopard-with-arc-enabled). I will most likely switch to ARC when OS X 10.8 is released.
  * I am not turning on AutoLayout constraints in my xib files until I drop 10.6 support.

## Credits ##
  * Contains json-framework/SBJSON library (http://code.google.com/p/json-framework/) embedded in it, source and all
  * Much guidance from Adrian Kosmaczewski blog (http://kosmaczewski.net/playing-with-http-libraries/)
  * Multipart features contributed by Adam Venturella
  * Sparkle automatic update framework (https://github.com/andymatuschak/Sparkle)