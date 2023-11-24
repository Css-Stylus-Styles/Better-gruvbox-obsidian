### Table of Content : 

- [Motivation  and Philosophy](#motivation)
- [Design decisions](#design)
- [How to install and use](#install)
        - [Install with git using command line](#git)
        - [Install by downloading the file](#git)

 ## Motivation  and Philosophy <a name= "motivation"></a>
Using obsidian was transformative experience for my productivity and personal development .Certainly most used program for me after maybe the broswer , however i see myself changing theme alot (*At the time of making this i had 7 themes installed*) i used seperate themes for ``dark`` and ``light `` modes and found most themes to be good for either light or dark mode 

i was into gruvbox theme lately and found it to be the best theme being easy on eyes as well as easy to read in for long sessions and since this is my most used app i decided to modify obsidian theme to fit my own preferences 

**I know that there are 3 themes when you search for gruvbox on obsidian but i found contrast issues and use of inconsistent colors a common thing across theese themes**

Although i might not be good at coding  but i took parts from other theme and even wrote some parts from scratch to make this theme possible


## Design decisions <a name= "design"></a>

Here are some considerations i had in mind while i was designing this 
 - Making something to use for a long hours (easy to read text , no contrast issues )
- Making sure theme follows [Gruvbox ](https://github.com/morhetz/gruvbox) color scheme very  closely (some alternative decisions are made for better readibility of text i.e *adding darker color for code blocks*)
- Every theme you install the ``headings`` from ``H1 to H6`` are diffrerent colors and when you switch themes its hard to tell **WAS THIS H4 or H5  ?? am i using different font size no??** -> to solve this i made all the headings follow a gradient  as shown here in the table 

| Heading Level | Color Name   |
|---------------|--------------|
| ``h1``            | Dark Orange  |
| ``h2``            | Dark Yellow  |
|`` h3``            | Dark Green   |
| ``h4``            | Dark Aqua    |
|`` h5 ``           | Dark Blue    |
|`` h6 ``           | Dark Purple  |



 **Fixed code blocks**
- For most themes the syntax highlighting is not unfiorm some colors like variables and functions dont match the rest of the theme (in my theme there are seperate identifiers for every components of progamming languages like `operators` , `variables`, `functions`, `strings ` and more ) 
using this approach you can have more control over the colors of code blocks

if you want to change specific colors in code blocks please refer to [How to modify](#modify) section for more details


## How to install and use  <a name ="install"></a>

####  I CAN USE GIT <a name="git"></a>

**Terminal git workflow**

 git clone 

```
https://github.com/bilalazh/Better-gruvbox-obsidian.git
```

place ``better gruvbox (neon).css`` file to ``drive:\{Path to your vault}\.obsidian\themes``

- inside your vault there should be a ``.obsidian`` folder , thats where your themes live inside ``themes `` folder  

Now hit ``ALT+SHIFT+O `` to change the theme and you should see the theme in the drop down 

#### What is Git ?? and terminal??? <a name = "!git"></a>
 so if you have no idea about how to use git clone or terminal  fear not installation manually is still super easy .Follow these steps 
- on github page you should see a clickable link to ``better gruvbox (neon).css`` click on this file
  
you should see a download button now  , once you have the  file ending in `.css ` 

![image](https://github.com/bilalazh/Better-gruvbox-obsidian/assets/139261053/1d9f5657-650b-4364-9366-680c7099dd3f)

the steps to place it at the right folder are same as earlier 


place ``better gruvbox (neon).css`` file to ``drive:\{Path to your vault}\.obsidian\themes``

- inside your vault there should be a ``.obsidian`` folder , thats where your themes live inside ``themes `` folder  

Now hit ``ALT+SHIFT+O `` to change the theme and you should see the theme in the drop down 



**Screenshots**

[[Add Screenshots]]



**How to modify**
If you want to modify theme i'll assume that you know some css and /or probably have done this before

- Consider making a copy of ``.css`` file and open the copy with your text editor of choice

open ``better gruvbox (neon).css`` with your favourite text editor `vs code`  , `neovim ` , `emacs` 

There are some colors that are not mentioned in  [Gruvbox ](https://github.com/morhetz/gruvbox) color theme , you are seeing them because they were in previous theme or i added them for better readability for cases like `Code blocks` in dark mode and `current line highlight color` is also a custom color as well

Every part of code is commented with semi-helpful comments that i will likely improve in the next iteration of this theme 




**Fonts I am using**

Here are the font that can be seen in screenshots

Interface font is  : georgia
Text Font is : HelvetivaNeue
Monospace font : Cascasdia code



**Accent color**: 
#4b4b06

- vs code workflow 
- manual workflow
**Thanks To Projects**

**TODOS**:

**FAQS**
- Will you make more variants of this ?
- Any plans to release this to official theme broswing page on Obsidian?
