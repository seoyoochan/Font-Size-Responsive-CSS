Font-Size - Responsive-CSS
==========================

Adjustable font size via css media queries. Keep text with proportional size on different screens. Scale to minimum readable size.

Demo: [JSFiddle][1]


  [1]: http://fiddle.jshell.net/dgJaK/1/show/
  
  

Sample Usage in HTML via class:


----------

    <head>
        <link rel="stylesheet" type="text/css" href="font-size.css" />
    </head>
    <body class="font-size-10">
      <h1 class="font-size-2">Heading</h1>
      <p>Text</p>
      <small class="font-size-12">Small</small>
    </body>

    
Sample Usage in SASS Compass(scss) file:


----------


    @import "_font-size.scss";
    h1{
    	@extend .font-size-2;
    }
    h2{
    	@extend .font-size-3;
    }
    h3{ 
    	@extend .font-size-4;
    }
    h4{
    	@extend .font-size-5;
    }
    h5{
    	@extend .font-size-6;
    }
    h6{
    	@extend .font-size-7;
    }
    
    small{
    	@extend .font-size-12;
    }
    
    html, body{
    	@extend .font-size-10;
    }
