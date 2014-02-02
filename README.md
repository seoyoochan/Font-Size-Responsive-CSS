Font-Size - Responsive-CSS
==========================

Adjustable font size via css media queries. Keep text with proportional size on different screens. Scale to minimum readable size.

Sample Usage:


----------
In HTML via class:
    &lt;head&gt;
        &lt;link rel="stylesheet" type="text/css" href="font-size.css" /&gt;
    &lt;/head&gt;
    &lt;body class="font-size-10"&gt;&lt;h1 class="font-size-2">&lt;/h1&gt;&lt;p&gt;&lt;/p&gt;&lt;small class="font-size-12"&gt;&lt;/small&gt;&lt;/body&gt;

    
In SCSS file:

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
