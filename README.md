# Legislators of Tomorrow at UVA's Website
Admin instructions, how to edit pages

 **** before you continue reading please make sure you know where the edit (to edit files) and commit (to publish) buttons are 
 
1) Editing information in pages
-go to the corresponding .html page, so each .html page (e.g. leadership.html) correspond with the actual page "our leadership page". 
-resources.html-> legislative resource page, index.html->about us/main page, workshop.html ->bill workshop, etc…

-To edit the “contact us” and “new & events tab”, on each .html page is the following:
<a href="https://uva.campuslabs.com/engage/organization/legislatorsoftomorrow/contact">Contact Us</a> 
<a href="https://www.facebook.com/LegislatorsofTomorrow/">Events & News</a>
Simply replace the “https://website.com”  with the desired URL.

-to edit text, just replace the old text. 

the following is from workshop.html

ex : h3 align="left">All are Welcome! Wednesday 6:30-7:30 PM at Monroe 118 &nbsp; </h3

the to change date just do this:

ex : h3 align="left">Come Visit Us! Monday 5:30-6:30 PM at Rice 118 &nbsp; </h3

* make sure you use add < infront of the above code (could not in this file or it would change font/style), e.g. <h3 ...> ...... <h/3>

make sure you keep all the syntax and characters as they are.
<br> = new line

2) Change images.

-For the main background image of Capitol Hill, upload a new image in the picture folder….

-Then go to the styles.css file and replace the following
url("./images/LoT_wallpaper.jpg")
with:  url("./images/new_picture.jpg")

-For the other images on the pages, go to the corresponding .html file and replace the image name with the new images uploaded corresponding folder.

-Change leadership.html images examples (images in the officers folder)
img class="card-img-top" src="./officers/Amy Cochran.jpg" alt="Card image cap">

-then change into: img class="card-img-top" src="./officers/new image.jpg" alt="Card image cap">

-For images on other .html pages that are uploaded in the “pictures” folder
src="./pictures/oldimage.jpg" then replace with new image src="./officers/newimage.jpg"

-Created by Andrew Zhang
