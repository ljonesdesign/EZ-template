# EZ-template
>This is a simple starter template for teaching html and css.

The [working sample site at opal.ils.unc.edu](https://opal.ils.unc.edu/~lblakej/website-helps/09-EZ-template/index.html)) has four pages that serve as a goal for you. This template only contains the ```index.html``` page.

You will have to create the pages by duplicating the ```index.html``` page three times and make changes to the few lines of code that can't be duplicated. You will also need to edit ```class="active"``` for each link in the ```topnav``` section to make each work

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

## Here are the steps:

1. If you understand git and have setup your computer to work with git, you can ```git clone``` the files. If you don't understand this, then just download the files to your computer.
2. Unzip (mac) or extract (PC) the folder.
3. Open the folder as a project in your text editor. *If you are using a text editor that does not allow you to open a project, then I assume you know how to work with the finder on your PC or Mac.*
4. Open your ```index.html``` file
  a. Edit the Title code. Where it says ```EZ Template Example``` Put in your first and last name.
  b. Edit the H1 tag as you wish
  c. Edit the first p tag as you wish
5. Save your ```index.html``` file. This is your home page. Do not name your home page home.html; keep it as ```index.html```; do not create a ```home.html``` page.
6. Next, you will create an empty ```about.html``` page. 
7. copy the code from your ```index.html``` page into your ```about.html``` page and save that page. 
8. You now have an about page, but since it is an **exact copy** of your ```index.html``` page, it does not work properly. You need to make some changes to the page. 
  a. Edit the Title code. Where it says ```Home Page``` change that to ```About Page```.
  b. Edit the H1 tag so that is is not referencing the Home Page. Make it reference the about page in some way.
  c. Remove ```class="active"``` and put it in the a tag of the About page.

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
  You now know how to create pages in the old fashioned way that is was done in the early 2000s. We build tools now, but this is good practice to see how complicated it used to be. 

