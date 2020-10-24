# Homework-1-Refactoring
**First homework assignment. Refactoring**

<br>
<br>
<br>

[Click here for the deployed application](https://jongudenzi.github.io/Homework-1-Refactoring/)
<br>
<br>

[Click here for the GitHub repository](https://github.com/JonGudenzi/Homework-1-Refactoring)
<br>
<br>
This website is an advertizing agency that helps businesses have more accessibility in their websites. Being that accessibility is what they offer, it is important that they themselves have this on their website. 

Our User Story for this project is to refactor a marketing agencies website to be better optimized for search engines.
Here is the user story given.

<img src="assets/images/userstory.PNG" width="380" height="100">
<br>
<br>
Nothing to the website's image will change with the code changes we make. The benefit of these changes will be strictly for accessibility purposes.
This is the current look of the website, which once again, will not change in design.
<br>
<img src="assets/images/01-html-css-git-homework-demo.png" width="300" height="500">
<br>
<br>
Several divs and classes had to be taken out and replaced with more semantic tags. Having more semantic tags will give this site more accessibility. Search engines will know that these semantic tags are more important.  This will cause less issues or errors than having divs and classes.
<br>
<br>

**Before with div and class:**
<br>
<img src="assets/images/div-to-main-and-section.PNG" width="800" height="200">
<br>

**After using main and section:**
<br>
<img src="assets/images/after-div-to-main-and-section.PNG" width="800" height="200">
<br>
<br>
Of course by doing this all css selectors will be changed from the class selectors that they had to the more semantic tags given.
<br>
<br>
<br>
<br>
The functionality of the page is also very important. We need to make sure all of the links and images, including attributes are working properly. 
In the case on this page, a link from the nav bar is not dirrecting to where it should. This is because a class is being used where at the part of the page it should be directed to when clicked. Because it's a class instead of an id this link will not work.  This will also be corrected as shown below.
<br>
<br>

**Before: Using class instead of id**
<br>
<br>
<img src="assets/images/section-class.png" width="700" height="100">

<br>
<br>

**After: Using id to correct direct link from the nav bar**
<br>
<br>
<img src="assets/images/section-id.png" width="500" height="100">
<br>
<br>
<br>
<br>
<br>
<br>
Page loading speed is important as well. By combining as many css selectors with identical properties as we can will speed up the load and refresh of the page. This will happen by reducing the amount of http requests from the browser.
Here is an example of this on this webpage.

**Before: Unconsolidated css**
<br>
<br>
<img src="assets/images/css-unconsolidated.png" width="900" height="400">

<br>
<br>

**After: Combined selectors with identical properties**
<br>
<br>
<img src="assets/images/css-consolidated.png" width="500" height="150">
<br>
<br>
As you can see it it unnecessary it have multiple tags of css when the properties are the same. This will only slow things down and it also makes it less confusing for other developers that might work on the same code later on.
This page should be much easier to understand the code now from a browser, search engine, and future developers on this site.  Not to mention the accessibility for disabled people. Website readers for the blind will also be able to read this code much more efficiently with no change to the actual look and layout of the page.