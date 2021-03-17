Read me file for landing page 

I used HTML5 ,CSS3 and javaScripte (ES6)

this project contain 3 files 

1-index.html
2-style.css
3-app.js


feature of project are usable across modern desktop, tablet, and phone browsers

page formed from number of section and depending on this number I create dynamic navigation bar

when we click on a nav link it scrolle to the correspondance section 

give active class for viewed section and its link 

frest thing we loop on list of sections to create list item and link and append these items to a fragment 

append this fragment to the nav_bar list ul

add click event listener on the list of nav bar

create scrollToSection function to be the callback function 

add scroll event listener to window and create toggleActiveState function to be the callback function

that toggle the active status of nav link and section using IntersectionObserver