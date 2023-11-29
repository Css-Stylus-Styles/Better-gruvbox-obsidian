### Table of Content : 

- [Motivation  and Philosophy](#motivation)
- [Design decisions](#design)
- [How to install and use](#install)
        - [Install with git using command line](#git)
        - [Install by downloading the file](#git)

 -[Screenshots](#ss) 
        - [Light Mode screenshots](#Light)
        - [Dark Mode screenshots](#Dark)

- [How to modify](#modify)
- [Font i used in the screenshots](#font)

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



## Screenshots <a name="ss"></a>

### Light Mode:<a name = "Light"></a>

**Spilt Screen view**

![light theme general dash board look ](https://github.com/bilalazh/New-Tab-Custom-Page/assets/139261053/c28a4fe5-e21a-4919-84ea-b6d8e5d79cf5)

**Graph View**

![light theme graph look ](https://github.com/bilalazh/New-Tab-Custom-Page/assets/139261053/6df9581a-16f1-4eb5-8e8e-a7f3e257f02e)



### Dark Mode : <a name = "Dark"></a>

**Spilt Screen view**

![dark  theme main dashboard ](https://github.com/bilalazh/New-Tab-Custom-Page/assets/139261053/e2561194-1186-4acc-8aa9-10da2374d830)


**Graph View**


![dark  theme graph look ](https://github.com/bilalazh/New-Tab-Custom-Page/assets/139261053/288aa36e-40b3-4644-ae20-3d28603fb433)


## How to modify <a name = "modify"></a>

If you want to modify theme i'll assume that you know some css and /or probably have done this before

- Consider making a copy of ``.css`` file and open the copy with your text editor of choice

open ``better gruvbox (neon).css`` with your favourite text editor `vs code`  , `neovim ` , `emacs` 

There are some colors that are not mentioned in  [Gruvbox ](https://github.com/morhetz/gruvbox) color theme , you are seeing them because they were in previous theme or i added them for better readability for cases like `Code blocks` in dark mode and `current line highlight color` is also a custom color as well

Every part of code is commented with semi-helpful comments that i will likely improve in the next iteration of this theme 




### Fonts I am using <a name= "fonts"></a>

Here are the font that can be seen in screenshots

- Interface font is  : `Georgia`
- Text Font is : `HelvetivaNeue`
- Monospace font : `Cascasdia Code`

**Accent color**: 

In the screenshots i am using as the accent color (this is not the part of gruvbox color scheme this is custom color used for better contrast )

`#4b4b06`

**Thanks To Projects**
This project was made possible thanks to these open source projects

- [obsidian](https://github.com/obsidianmd) 
- [gruvbox](https://github.com/morhetz/gruvbox)


**FAQS**
- Will you make more variants of this ?

Maybe its  just a Recency bias but so far i have been enjoying this theme very much , along with Recency bias it can be due to the fact that i made it and its custom tailored to suit me , but if i see fit i am going to make changes or rewrite this 


- Any plans to release this to official theme broswing page on Obsidian?

At this current point in time i have no idea how to do it , its in my TODO list and once this quesiton is removed from here , trying searching the theme in obsidian theme store you should find it 
