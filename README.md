### Table of Content : 

- [Motivation  and Philosophy](#motivation)
- [Design decisions](#design)
- [How to install and use](#install)

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



 - terminal git workflow
[[general path to your .obsidian folder]]

- how to download and work with zip

- Obsidian themes??

**Screenshots**

[[Add Screenshots]]



**How to modify**



**Fonts I am using**

**Accent color**: 
#4b4b06

- vs code workflow 
- manual workflow
**Thanks To Projects**

**TODOS**:
- Way to change the color of Titles(See other themes for this )

**FAQS**
- Will you make more variants of this ?
- Any plans to release this to official theme broswing page on Obsidian?
