# chu-zhang.github.io

Here is the instruction

<h2><ul><li>Open the website</li></ul></h2>

The Github website: www.github.com<br>

<ul><li>click the log in button, which is in the right top corner</li></ul>
<ul><li>Enter the email address and password, click log in button</li></ul>
<ul><li>on the dashborad page, click the chu-zhang/chu-zhang.github.io, which is in the left hand side</li></ul>
<ul><li>click index.html, where we organize the content of the website</li></ul>
<ul><li>click the pencil button( which in the right hand side of the page) to edit the code</li></ul>
<img width="204" alt="image" src="https://github.com/chu-zhang/chu-zhang.github.io/assets/82868869/d28ff8a6-f7ce-4f15-afe7-f362130d4316">
<ul><li>Here we have two button, edit and preview, edit is for changing the code, and preview is for view the website</li></ul>
<ul><li>After changing the code, click the commit changes button to save your code, and the website will update automatically in few mins</li></ul>
<img width="1440" alt="image" src="https://github.com/chu-zhang/chu-zhang.github.io/assets/82868869/abebb269-9c86-427b-b2be-4e0be50c2f90">




<h2><ul><li>The function we will use</li></ul></h2>

```
<a href>name</a>
```
<li> This function is to link the button (which is the name) with the pdf/website/the section of the website,</li><br>

```
<section id=""></secttion>
```
The section function is to seperate the content of the website into parts, and we name each by by changing the id names. We could use the a href function to link the section by have the same name for id and href address, and the href="#name", # is essential when we want to link the section<br>

```
.functionname{}
class="functionname"
```
The first row is based on css ( where we could change the type of the words), it will create a new function names functionames.<br>
After create it on css, then we could use it by adding class="functionname", for example:

```
<p class="functionname">content</p>
```
The p tag is an HTML element that represents a paragraph,by adding the class="functionname", we could change the type of words which is list in the special p function

```
<div></div>
```
div doesn't represent anything, it just help us to group the content, and we could use the class function and id more convenient.
<h2><ul><li>For editing the directory page</li></ul></h2>

In the left hand side of the personal website, we have the button: Contact, education,work experience, publication and working papers.
<img width="217" alt="image" src="https://github.com/chu-zhang/chu-zhang.github.io/assets/82868869/02e9f6e7-6ae2-4f83-a5f3-7fde65554a1e"><br>

In order to edit it, please go to the code line 19, where we could find the Navigation bar.<br>

<img width="1066" alt="image" src="https://github.com/chu-zhang/chu-zhang.github.io/assets/82868869/327d8746-f4a3-474a-912e-960e4cd08c90">


In order to add the new button, we just need to add an extra code between line 30 and 35.

```
<li class="nav-item"><a class="nav-link js-scroll-trigger" href="#page-top"> Contact </a></li>
```
Here, the only thing we need to change is href="#page-top"( which we will describe it later) and Contact ( what we name the button)<br>



The order of the button is depends on the order of the code, so you could organize the order by change the order of the code.

<h2><ul><li>Main content</li></ul></h2>
Based on the code, we divided the code into 5 parts, and we use the code 

```
<section id="the name you want to use">
  <the code you want to write in this part>
</section>
```
the section function is the way to seperate your whole content into several parts.<br>

and the id is the default that to name the section, which could help us to use the buttion in the directory page.<br>

For example, 
```
<li class="nav-item"><a class="nav-link js-scroll-trigger" href="#test1"> TEST </a></li>
<section id="test1">
  <the code you want to write in this part>
</section>
```

Here, we named the section as "test1", and the href="#test1", and the button name is called TEST. <br>
Everytime we change it, we have to make sure the button is connect to the section. Once the href equal to "#id", then the button and section part is matched.

<h3><ul><li>Adding the Publication</li></ul></h2>

go to the line 108, where we start the publication section
Let's look at an example:

```
<div class="resume-item d-flex flex-column flex-md-row mb-5">
				<div class="resume-content mr-auto">
          <h4 class="mb-0"><a href="https://doi.org/10.1016/j.jmoneco.2023.06.005"> The macroeconomic announcement premium and information environment (with Shen Zhao) </a></h4>
          <div class="subheading mb-3"> Journal of Monetary Economics, forthcoming. </div>
        </div>
				<div class="resume-date text-md-right">
					<span class="text-primary"> 2023 </span>
				</div>
</div>
```
And the thing we need to focus is:

```
<h4 class="mb-0"><a href="https://doi.org/10.1016/j.jmoneco.2023.06.005"> The macroeconomic announcement premium and information environment (with Shen Zhao) </a></h4>
					<div class="subheading mb-3"> Journal of Monetary Economics, forthcoming. </div>
     <span class="text-primary"> 2023 </span>
     
```

We only need to change 3 items<br>
<li>first is the href, we need to replace it into the new doi website that could view the papers.</li><br>
<li>Second, is the title in "a" function, inside the a function, we have the title :The macroeconomic announcement premium and information environment (with Shen Zhao), which is the name of the paper, we could display the name of papers by changing the title.</li><br>
<li>Third is the number inside the span function.</li>





