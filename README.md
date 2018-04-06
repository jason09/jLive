<div class="doc-content">

<div class="content-inner">

<section id="download-section" class="doc-section">

## Download

<div class="section-block">

JLive is a cross-platform JavaScript library designed to simplify the client-side scripting of HTML. It is free, open-source software using the permissive MIT License. JLive's syntax is designed to make it easier to navigate a document, use PHP useful functions, select DOM elements, create animations, handle events, form validation, and develop Ajax applications.  
JLive also provides capabilities for developers to create plug-ins on top of the JavaScript library.

[Visit Web Site](https://jlive-lib.com/ "Visit Web Site")</div>

</section>

<section id="installation-section" class="doc-section">

## Installation

<div id="step1" class="section-block">

### Step One

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis.

<div class="code-block">

###### Default code example:

`bower install <package>`

`npm install <package>`

</div>

</div>

<div id="step2" class="section-block">

### Step Two

The JLive library is a single JavaScript file containing all of its common DOM, PHP useful function, event, and Ajax functions. It can be included within a Web page by linking to a local copy or to one of the many copies available from public servers.

</div>

<div class="code-block">

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

</div>

<div id="usagestyle" class="section-block">

### Usage styles

*   Via the **$j function** , which is a factory method for the JLive object. These functions are chainable as they all return jlive objects.
*   Via **$j.-prefixed functions**. These are PHP functions and others utility functions.

Access to and manipulation of multiple DOM nodes in JLive typically begins with calling the $j function with a CSS selector string. This returns a JLive object referencing all the matching elements in the HTML page. $j("div .test"), for example, returns a JLive object with all the div elements of class test. This node set can be manipulated by calling methods on the returned JLive object or on the nodes themselves.

<div class="code-block">

###### JS Code Example

        ...
       <script>
       //Via the $j function
    	$j('#myDiv').style({'color':'#fff','background':'#222'});

        //$j.-prefixed functions 
    	$j.ucwords('jlive library');
       </script>
        ...

</div>

</div>

</section>

</div>

</div>
