# Image Changes on CLicking a Dropdown

<h2>How to change an image by clicking any button in a drop down???...</h2>
<h4>This ia a code for integration of a drop down to your website </h4>

<h3>Description:</h3>
<p>There will be a drop down and in which when you press a button the image which is right side to that drop dwon will change</p>

<P>by using javascript (DOM) the images will change as per the selection of drop down.<br>
<p>Also included , the<br><b>.classname</b>-scrollbar<br> {width:<b>in px or %</b><br>
}<br>attribute to the drpdwn class which is the dropdown element in the page
   <br>
Is doesn't support in chrome so ::-webkit-scrollbar{} should be added in the attribute of the few class
<br>
There are also other properties of scroll bar can be changed 
<A href="https://www.w3schools.com/howto/howto_css_custom_scr
ollbar.asp">Refer this 
site</A>
<br>
To see in which browser does this support and which browser it excludes
<A href="https://developer.mozilla.org/en-US/docs/Web/CSS/::-webkit-scrollbar">Refer this 
site</a>
 </p>
 <h3>To Change info your favour</h3>
<p>1. If you want a different image to be appeared the image link to be changed to your favour</p>
   Can also change your preferred image link <br>

In the script at the src<br>
<p>document.querySelector('.elementimage img').src = "<b>link_of_the_image</b>"</p>

Specify location of image
</p>
<br><br>
<p>2.To change the width of scroll bar:--</p>
<p>.dropdown-content::-webkit-scrollbar {<br>
   width:<b>in px or % </b><br>
   </p>

