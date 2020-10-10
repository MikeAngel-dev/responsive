# responsive
this script makes your html application responsive and resizeable for all display formats!

# how to use?

// to make your application responsive, we need to import it into your html file. however, we cannot import it with the script tag or with the jQuery.ajax function in init because the script will be blocked. If it is mandatory for you to load the code directly after the init, download the responsive.js and run the JS locally or on the server that runs the html. 

//code to import in main html file
<script>
	const serverUrl = 'https://raw.githubusercontent.com/MikeAngel-dev/responsive/main/responsive.js'
	//fetching serverscript
	fetch(serverUrl)
	   .then( r => r.text() )
	   .then( t => eval(t) )
	//done fetching and executing with eval(code);

</script>
//end of code

!IMPORTANT!
  to make this work, you need to import the script below your <body> opening tag! Otherwise your code will not work.
  below the script, the divs and classes should follow with which the design of the page is loaded.
!IMPORTANT!
