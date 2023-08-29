# chu-zhang.github.io

Here is the instruction

<h2><ul><li>For editing the directory page</li></ul></h2>

In the left hand side of the personal website, we have the button: Contact, education,work experience, publication and working papers.
<img width="217" alt="image" src="https://github.com/chu-zhang/chu-zhang.github.io/assets/82868869/02e9f6e7-6ae2-4f83-a5f3-7fde65554a1e"><br>

In order to edit it, please go to the code line 19, where we could find the Navigation bar.<br>

In order to add the new button, we just need to add an extra code.

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



