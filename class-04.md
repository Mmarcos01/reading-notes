## HTML Links

Links are created using the \<a> element which has an attribute called href- which will hold the outside page you wish the user to link to, or **absolute url**.  
**Ex:**
\<a href="http://www.weblink.com">Text to link goes here.\</a>  

When linking to a page within the same site you can use a shorthand known as **relative url** If all pages are in the same folder, the href attribute is just the name of the file.  

**Ex:**
\<a href="index.html">Home\</a>
\<a href="about.html">About\</a>  

**URL** - Uniform Resource Locator

### Email Links

To create a link that starts up the user's email program and addresses an email to a specific email address, the href attribute will start with mailto: followed by the email address you want the email to be sent to.  

**EX:**
\<a href="mailto:you@example.org">Email to you\<a>

### Open Link in New Window

To create a link that opens up in new window, use the **target** attribute on the opening \<a> tag. The value should be _blank.  

**EX:**
\<a href="http://www.imdb.com" target="_blank">Email to you\<a>


### Linking to a Specific Part of the Same Page

You need to first identify the parts of the page to link to, using the **id attribute.**  

**Ex:**

\<h1 id="top">Top Header\</h1>
\<p>\<a hred= "#top">Goes to Top Header\</a>\</p>

### Linking to a Specific Part of Another Page
