<!DOCTYPE html>
<html lang="en">
  <head>
  <meta charset="utf-8">
  <title>How Browsers Work</title>
  <a href="http://www.html5rocks.com/en/tutorials/internals/howbrowserswork/"></a>
  </head>
  <body>
  
   <h1>Types of browsersin the market</h1>
   
  <p>here are five major browsers used on desktop today: Chrome, Internet Explorer, Firefox, Safari and Opera. On mobile, the main browsers are Android Browser, iPhone, Opera Mini and Opera Mobile, UC Browser, the Nokia S40/S60 browsers and Chrome–all of which, except for the Opera browsers, are based on WebKit. I will give examples from the open source browsers Firefox and Chrome, and Safari (which is partly open source). According to StatCounter statistics (as of June 2013) Chrome, Firefox and Safari make up around 71% of global desktop browser usage. On mobile, Android Browser, iPhone and Chrome constitute around 54% of usage. </p>
  
  
  <h2>Browsers Main Functionality</h2>
  
  <p>The main function of a browser is to present the web resource you choose, by requesting it from the server and displaying it in the browser window. The resource is usually an HTML document, but may also be a PDF, image, or some other type of content. The location of the resource is specified by the user using a URI (Uniform Resource Identifier). </p>
  
  
  <h3>browser's high level structure</h3>
  
  <p>1.The user interface: this includes the address bar, back/forward button, bookmarking menu, etc. Every part of the browser display except the window where you see the requested page. </p>
  
  <p>2.The browser engine: marshals actions between the UI and the rendering engine.</p>
  
  <p>3.The rendering engine : responsible for displaying requested content. For example if the requested content is HTML, the rendering engine parses HTML and CSS, and displays the parsed content on the screen.</p>
  
  <p>4.Networking: for network calls such as HTTP requests, using different implementations for different platform behind a platform-independent interface.</p>
  
  <p>5.UI backend: used for drawing basic widgets like combo boxes and windows. This backend exposes a generic interface that is not platform specific. Underneath it uses operating system user interface methods.</p>
  
  <p>6.JavaScript interpreter. Used to parse and execute JavaScript code.</p>
  
  <p>7.Data storage. This is a persistence layer. The browser may need to save all sorts of data locally, such as cookies. Browsers also support storage mechanisms such as localStorage, IndexedDB, WebSQL and FileSystem.</p>
  
  
  </body>
</html>
