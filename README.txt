## 16442178 Arnaud Fontane


## Synopsis
Northampton University - Web development CSY1018 - Assignment 1 - Personal Online CV

A presentation of my skills my experience and education - as part of Northamtpon University Web development first assignment.


## Code Example
<header>
    <nav id="dropdown1">
      <ul id="navbar">
        <li><a href="../index.html">Home</a></li>
        <li><a href="bio.html">bio</a></li>
        <li><a href="contact.html">contact></a></li>
        <li class="dropdown"><a href="cv.html">cv</a></li>
    </ul>
  </nav>
</header>

<main>
<!--MY PAGE CONTENT-->
</main>

<footer>
	<!--LINKS TO SOCIAL MEDIA AND MY GITHUB-->
	<a href="https://github.com/GitUser2345/csy1018-assign1">
        	<img class="ico1" src="../img/gi.png" alt="github_icon">
      	</a>
</footer>

All my html pages have the above structure NAVBAR /CONTENT /LINKS

body {
    margin: 0px;
    padding: 0px;
    cursor: crosshair;
    letter-spacing: 2px;
    word-spacing: 6px;
}

/*NAVBAR STYLING>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>*/

#dropdown1 {
    z-index: 10;/*NAVBAR ON TOP OF EVERYTHING*/
}

/*NAVBAR BEHAVIOR*>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>*/
#dropdown1:hover {
    width: 50%;
    height: 120%;
    background: white;
    transition-property: width, height;
    transition-duration: 0.25s;
    transition-timing-function: ease-out;
}
/*MAIN STYLING>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>*/
main_content1{
}
main_content2{
}
main_contentN{
}

/*FOOTER STYLING>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>*/
footer {

}
.ico1 {
}

.ico1:hover {
}


All my css file all share the above structure BODY DEFAULT PROPERTY CANCELLATION/ NAVBAR STYLING/ NAVBAR BEHAVIOUR/ MAIN CONTENT STYLING/ FOOTER STYLING

## Motivation
My main motivation was to gain as much developping skills as possible in html5 and css.
I want those skills to match  the quality of the leading edge trends on the web. 

I guess this what the first assignment of CSY1018 is about.


## Tests
1 I checked if the visual of my pages was what I expected if not I debug my html code and css file.
	If 1 is OK
2 I go on W3 markup validator and upload and verify my html page 
	If 2 is OK
3 I go on W3 css jigsaw validator and upload and verify my css file
	If 3 is OK
4 I repeat the process from 1 for my next page
 

## Contributors
https://material.io/guidelines/					all pages transitions and shadows
http://manualcreative.com/project/google-design/		all pages colors	
https://awwwards.com						navbar style and parallax effect
http://www.w3schools.com/howto/tryhow_css_parallax_demo.htm	parallax effect
http://cuberto.com/projects/					cv page date layout
stackoverflow.com						debugging

## License
Northampton University