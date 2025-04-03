<html lang="en">
<!-- this file must be atleast 20 lines long -->

<!-- Must contain atleast 4 elements in the body-->

<!-- create a specific web page "project1.html" describing a project you did or plan to do soon -->

<!-- front page cannot significantly borrow from your project1.html -->

<!-- project1.html needs atleast 3 headings that are underlined, including a main heading that is aligned to the center of the page body, and uses a 28pt bold font. The others on the page are left-aligned and appear in an 20pt normal font.-->

<!-- All headings on the project page should use a specific foreground color and a specific background color -->

<!-- The font families for headings are Century Gothic, Futura, Verdana, or any sansserif font available on the system. -->

<!-- The overall page's body should have a white background. Text in the body should have a specific foreground color that is different from the headings’ foreground/background color, and use an 14pt font. The font families for page text are Georgia, Garamond, or any serif font available on the system. -->

<!-- Any links on the page should use the color matching the color of the page headings. -->
<!-- your project presentation, needs to include at least one picture on the page. You need to use absolute URL(s) to link to the picture(s); (like on a real server) don't link to relative URL(s) on your hard drive. -->

<!-- At the bottom of your project page, you need to have at least one “Home” link, which should link to your index.html page. For this “Home” link, you need to use a relative URL and assume it is located on the same web site as project1.html. -->
<!--  -->
<!--  -->
<head>
<style>
	*,
*::before,
*::after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
	body, html {
	}
	body {
		Display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	.button {
		display: inline-block
		padding: 20px 40px;
		font-size: 16px;
		color: black;
		text-align: center;
		text-decoration: none;
		border-radius: 20 px;
		margin-top: 20 px;
	}
	main {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100 vw;
  height: 100 vh;
}

.card {
  width: 50px;
  height: 20px;
  margin: 0px 10px;
  background-color: transparent;
  cursor: pointer;
  position: relative;
  top: 0px;
  left: 0px;
  border-radius: 50px;
  box-shadow: 1px 1px 5px 0px rgba(24, 40, 87, 255);
  transition: all 150ms ease-in-out;
}
.card:hover {
	top: -3px;
	left: -3px;
  box-shadow: 3px 3px 15px 0px rgb(21, 2, 55);
}
.card:active {
	top: 10px;
	left: 10px;
	background-color: navy;
	box-shadow: inset 0 0 10px rgba(24, 40, 87, 255);
	text-align: center;
	color: white;
}
a:link, a:visited {
    color: black;
    text-align: center;
    text-decoration: none;
    display: inline-block;
}

div.background {
 	 background: lightblue url(https://i.imgur.com/LyklLIB.jpeg) no-repeat center;
 	 background-size: cover;
  	align-items: center;
 	 display: flex;
 	 justify-content: center;
 	 height: 1000px;
 	 width: 1000px;  	
}
	.navbar a {
		float: left;
		display: block;
		color: black;
		text-align: center;
		padding: 14px 20px;
		text-decoration: none;
	}
	.navbar a:hover {
		background-color:rgba(195, 32, 51, 255)
		color: black;		
	}
	.h1 {
		display: inline-block
		padding: 20px 40px;
		font-size: 72px;
		color: black;
		text-align: center;
		text-decoration::backdrop
		border-radius: 20px;
		margin-top: 20px;

	}
</style> 
<title>
Module #4 HTML assignment
</title>
<!-- use <span> elements around my headings and in my CSS document formatted all of the <span> elements withe the background-color element. This allowed for only the text to have a background color improving appearance and legibility. I also used this element to change the body background-color to make my index.html more vibrant.-->

  </head>
	<body>
		<h1>Welcome to my Page</Wbr></h1>
	
<p>Assignment #4 - Rhett Taylor</p>
<div class="background">
	<main>
  <div class="card">
    <center><a href="project1.html">Enter</a></center>
  </div>
  </main>

