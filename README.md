<!-- If you have downloaded this template from github, and 
can see this in your editor, don't use it for step by step
instructions. It is not formatted for reading in your text editor
copy this link go to live page here: https://github.com/ljonesdesign/EZ-template -->

# EZ-template
>This is a simple starter template for teaching html and css.

The [working sample site at opal.ils.unc.edu](https://opal.ils.unc.edu/~lblakej/website-helps/09-EZ-template/index.html) has four pages that serve as a goal for you. This template only contains the ```index.html``` page.

You will have to create the other three pages by duplicating the ```index.html``` page three times and make changes to the few lines of code that can't be duplicated. You will also need to edit ```class="active"``` for each link in the ```topnav``` section to make each work properly.

The Links to the other three pages have been provided in the ```topnav``` code section:

## Topnav code "as is"

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

## Topnav code "aligned for analysis"
Notice by the lines and spacing below that this is logically and neatly sorted into multiple levels. There is an ```<a></a>``` element nested inside an ```<li></li>``` and these are nested in a ```<ul></ul>``` element:

```
<!-- Start of Navigation code -->

<ul class="topnav">  
                                               
                                           | only this|
                                           | is shown |
                 | attr.  =  "page.html"   | to user  |
   _______ <a __________________________ > __________________________
   <li>  | <a    | href   =  "var1.html" > | Var 1    | </a>  </li>
   <li>  | <a    | href   =  "var2.html" > | Var 2    | </a>  </li>
   <li>  | <a    | href   =  "var3.html" > | Var 3    | </a>  </li>
   <li>  | <a    | href   =  "var4.html" > | Var 4    | </a>  </li>

</ul>

<!-- End of Navigation code -->
```
Everything matters. This code would not work because of the ```-``` ```_``` and ```|``` characters, but it would work if they were removed because html disregards spaces.

## Topnav code "minified"

And it would also work if we removed all spaces crunching it onto one line:

```
<ul class="topnav"><li><a class="active" href="index.html">Home</a></li><li><a href="about.html">About</a></li><li><a href="classes.html">Classes</a></li><li><a href="interests.html">Interests</a></li></ul>
```

This is called **minifying** code and it will help your code run faster. Many templates that you use will have code with spaces and code that has been minified. Minified code is very difficult to edit, so you would use the non-minified code for your 02.03 project. [Beautifying](http://minifycode.com/html-beautifier/) code is the process of reversing the process of [minfying](http://minifycode.com/html-minifier/) code.

## Topnav code "focus on active class"

Let's get rid of some of the lines and spaces (except for the spacing for the ```class="active"```) and try to grasp how the "*you are here*" logic works with css and navigation using the ```active``` class.

*Var1 is active:*

```
   <li><a class="active" href="var1.html">Var 1</a></li> <!-- when viewing -->
   <li><a                href="var2.html">Var 2</a></li>
   <li><a                href="var3.html">Var 3</a></li>
   <li><a                href="var4.html">Var 4</a></li>
```

*Var 2 is active:*

```
   <li><a                href="var1.html">Var 1</a></li>
   <li><a class="active" href="var2.html">Var 2</a></li>  <!-- when viewing -->
   <li><a                href="var3.html">Var 3</a></li>
   <li><a                href="var4.html">Var 4</a></li>
```

*Var 3 is active:*

```
   <li><a                href="var1.html">Var 1</a></li>
   <li><a                href="var2.html">Var 2</a></li>
   <li><a class="active" href="var3.html">Var 3</a></li>  <!-- when viewing -->
   <li><a                href="var4.html">Var 4</a></li>
```
 
 *Var 4 is active:*
 
```
   <li><a                href="var1.html">Var 1</a></li>
   <li><a                href="var2.html">Var 2</a></li>
   <li><a                href="var3.html">Var 3</a></li>
   <li><a class="active" href="var4.html">Var 4</a></li>  <!-- when viewing -->
```


## Here are the steps to build out the other pages

### Before doing the steps, get a feel for how the ```class="active"``` attribute operates in real time while moving around the site
Go to the [sample site](https://opal.ils.unc.edu/~lblakej/website-helps/09-EZ-template/index.html) and click all of the pages in the top menu bar. For each page, view the source and look specifically at the Navigation code for the page you are on. Also be sure to notice that the page is changing in the URL bar. If you are on the ```classes.html``` page, you will see an ```active``` class next to the classes link. That is how the browser knows how to make each tab stand out. So the rule is this: if you are editing ```classes.html``` that page needs to have the ```active``` class. If you make mistakes with the ```active``` class settings, your navigation will still work, but it will be wonky until you get the errors fixed.

### The ```index.html``` is your template in a template
The majority of the ```index.html``` file is a good template for creating your other pages. So copy it as many times as you need pages. In this sample project you will need to copy the code into an ```about.html``` page a ```classes.html``` page and an ```interests.html``` page. You must name the files as **all lowercase** for it to match the provided **all lowercase** code in the template. 

>OPAL is strictly case sensitive on file names. Your local computer development environment will match ```about.html``` with ```About.html```, but OPAL will not.

### Start working it out. It will start to make sense as you go along...

1. Download and Unzip (mac) or extract (PC) the folder.
2. Open the folder as a project in your text editor. *If you are using a text editor that does not allow you to open a project, then I assume you know how to work with the finder on your PC or Mac.*
3. Open your ```index.html``` file
5. Connect the page to your style.css page. Remove the comment and replace it with the following:```<link rel="stylesheet" href="style.css">```
6. Edit the Title code. Where it says ```EZ Template Example``` Put in your first and last name.
7. Edit the contents of the ```<h1> </h1>``` tag as you wish
8. Edit the contents of the  ```<p> </p> ``` tag as you wish
9. Find and Change to a different [Google font](https://fonts.google.com/) if you wish. *You can change it later, but you will have to make changes to all of your pages if you don't do it before you start the duplication process.*
10. Save your ```index.html``` file. This is your home page. Do not name your home page home.html; keep it as ```index.html```; do not create a ```home.html``` page.
11. Next, you will create an empty ```about.html``` page. 
12. copy the code from your ```index.html``` page into your ```about.html``` page and save that page. 

You now have an about page, but since it is an **exact copy** of your ```index.html``` page, it will not appear different if you click the link. You need to make some changes to the page so it looks like a new page.

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
Repeat this process for the other pages. You now know how to create pages in the old fashioned way that was done in the early 2000s. Modern websites use partials with build tools now, but this is good practice to see how complicated it used to be. You can use this EZ template for your project, but it will be a lot more limiting for you than what you can accomplish with a template with more features. 
 
 ## Editing the CSS file
  
The ```style.css``` file has helpful comments for you so that you will be able to change the colors and/or fonts for your new site. Just change them in the ```style.css``` file, and they will affect every page. That is because when you duplicated all of your pages, you copied the link to the ```style.css``` and the link to the google font that was in your ```index.html``` file.
