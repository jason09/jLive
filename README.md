Download client-side
--------------------

JLive is a cross-platform JavaScript library designed to simplify the client-side scripting of HTML. It is free, open-source software using the permissive MIT License. JLive's syntax is designed to make it easier to navigate a document, use PHP useful functions, select DOM elements, create animations, handle events, form validation, and develop Ajax applications.  
JLive also provides capabilities for developers to create plug-ins on top of the JavaScript library.

[Visit Web Site](https://jlive-lib.com)

Installation & Usage
--------------------

### Step One ( NODEJS )

JLive can be used as backend with NODEJS, here is all [available functions for NODEJS](https://jlive-lib.com/php_function.php).

###### Default code example:

`npm i jlive`

###### NODEJS Code Example

    import { JlivePHP } from 'jlive';
    JlivePHP.ucwords('jlive library');
    										
    										

### Step Two (Client-side)

The JLive library is a single JavaScript file containing all of its common DOM, PHP useful function, event, and Ajax functions. It can be included within a Web page by linking to a local copy or to one of the many copies available from public servers.

###### HTML Code Example

    <!DOCTYPE html> 
    <html lang="en"> 
        ...
       <script src="jlive.js"></script>
           <!-- OR --->
    	   
                  <!-- https://code.jlive-lib.com/jlive.prod-{version}.js --->
       <script src="https://code.jlive-lib.com/jlive.prod-0.0.2.js"></script> <
        ...
    </html>

### Client-side Usage

JLive has two usage styles:*   Via the **$j function** , which is a factory method for the JLive object. These functions are chainable as they all return jlive objects.
*   Via **$j.-prefixed functions**. These are PHP functions and others utility functions.

Access to and manipulation of multiple DOM nodes in JLive typically begins with calling the $j function with a CSS selector string. This returns a JLive object referencing all the matching elements in the HTML page. $j("div .test"), for example, returns a JLive object with all the div elements of class test. This node set can be manipulated by calling methods on the returned JLive object or on the nodes themselves.

###### JS Code Example

    
        ...
       <script>
       //Via the $j function
    	$j('#myDiv').style({'color':'#fff','background':'#222'});
         
        //$j.-prefixed functions 
    	$j.ucwords('jlive library');
       </script>
        ...
