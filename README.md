<!-- If you have downloaded this template from github, and 
can see this in your editor, don't use it for step by step
instructions. It is not formatted for reading in your text editor
copy this link go to live page here: https://github.com/ljonesdesign/EZ-template -->

# EZ-template
>This is a simple starter template for teaching html and css.

The [working sample site at opal.ils.unc.edu](https://opal.ils.unc.edu/~lblakej/website-helps/09-EZ-template/index.html) has four pages that serve as a goal for you. This template only contains the ```index.html``` page.

You will have to create the other three pages by duplicating the ```index.html``` page three times and make changes to the few lines of code that can't be duplicated. You will also need to edit ```class="active"``` for each link in the ```topnav``` section to make each work properly.

The Links to the other three pages have been provided in the ```topnav``` code section:
```
<!-- Start of Navigation code -->

  <ul class="topnav">
   <li><a class="active" href="index.html">Home</a></li>
   <li><a href="about.html">About</a></li>
   <li><a href="classes.html">Classes</a></li>
   <li><a href="interests.html">Interests</a></li>
  </ul>

<!-- End of Navigation code -->
```
>Notice that this has multiple levels. There is an ```<a></a>``` element nested inside an ```<li></li>``` and these are nested in a ```<ul></ul>``` element.

## Here are the steps to build out the other pages:

### Before doing the steps, get a feel for how the ```class="active"``` attribute operates.
Go to the sample site and click all of the pages in the top menu bar. For each page, view the source and look specifically at the Navigation code for the page you are on. If you are on the classes.html page, you will see an ```active``` class next to the classes link. That is how the browser knows how to make each tab stand out. So the rule is this: if you are editing ```classes.html``` that page needs to have the active class. If you make mistakes your navigation will still work, but it will be wonky if you don't go back and fix your errors. 

### The ```index.html``` is your template in a template
The majority of the ```index.html``` file is a good template for creating your other pages. So copy it as many times as you need pages. In this sample project you will need to copy the code into an ```about.html``` page a ```classes.html``` page and an ```interests.html``` page. You must name the files as all lowercase for it to match the code in the template. OPAL is strictly case sensitive on file names. Your local computer development environment will match ```about.html``` with ```About.html```, but OPAL will not.

### Start working it out. It will start to make sense as you go along...

1. If you understand git and have setup your computer to work with git, you can ```git clone``` the files. If you don't understand this, then just download the files to your computer.
2. Unzip (mac) or extract (PC) the folder if you did not do the ```git clone``` option.
3. Open the folder as a project in your text editor. *If you are using a text editor that does not allow you to open a project, then I assume you know how to work with the finder on your PC or Mac.*
5. Open your ```index.html``` file
6. Edit the Title code. Where it says ```EZ Template Example``` Put in your first and last name.
7. Edit the H1 tag as you wish
8. Edit the first p tag as you wish
9. Find and Change to a different [Google font](https://fonts.google.com/) if you wish. *You can change it later, but you will have to make changes to all of your pages if you don't do it before you start the duplication process.*
10. Save your ```index.html``` file. This is your home page. Do not name your home page home.html; keep it as ```index.html```; do not create a ```home.html``` page.
11. Next, you will create an empty ```about.html``` page. 
12. copy the code from your ```index.html``` page into your ```about.html``` page and save that page. 

You now have an about page, but since it is an **exact copy** of your ```index.html``` page, it does not work properly. You need to make some changes to the page. 

1. Edit the Title code. Where it says ```Home Page``` change that to ```About Page```.
2. Edit the H1 tag so that is is not referencing the Home Page. Make it reference the about page in some way.
3. Remove ```class="active"``` and put it in the a tag of the About page.

How it should look in the ```index.html``` page:
```
<ul class="topnav">
   <li><a class="active" href="index.html">Home</a></li>
   <li><a href="about.html">About</a></li>
   <li><a href="classes.html">Classes</a></li>
   <li><a href="interests.html">Interests</a></li>
  </ul>
  ```
  How it should look in the ```about.html``` page:
  
  ```
<ul class="topnav">
   <li><a href="index.html">Home</a></li>
   <li><a class="active" href="about.html">About</a></li>
   <li><a href="classes.html">Classes</a></li>
   <li><a href="interests.html">Interests</a></li>
  </ul>
  ```  

### Continue if you wish, or move onto a better template
Repeat this process for the other pages. You now know how to create pages in the old fashioned way that is was done in the early 2000s. We build tools now, but this is good practice to see how complicated it used to be. You can use this EZ template for your project, but it will be a lot more limiting for you that what you can accomplish with a more template with more features. 
 
 ## Editing the CSS file
  
The ```style.css``` file has helpful comments for you so that you will be able to change the colors and/or fonts for your new site. Just change them in the ```style.css``` file, and they will affect every page. That is because when you duplicated all of your pages, you copied the link to the ```style.css``` and the link to the google font that was in your ```index.html``` file. 
 

