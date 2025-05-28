# DropdownMenu_Project_1
Building a dropdown menu. Diving into positions, display, z-index and finding an easy workflow

## Tuesday | 27-5-2025 | 20:06
Today I realised I have to dive into several subjects to be able to build a dropdown menu without getting stuck for hours...
## Subjects I need to understand better:
1. Position
2. Display
3. Top, Bottom, Left and Right
4. z-index
5. Order of elements (nav, div, ul, span, li, a)
6. Anatomy of  navigationbar and dropdown menu

### I would like to build this design
![image](https://github.com/user-attachments/assets/f819cba4-127a-440d-ac33-8d567b807e67)

But I got this far<br>
![image](https://github.com/user-attachments/assets/053f7b81-edb6-4411-a5e8-f6714e06e1f2)

With <code>position:absolute;</code> and <code>Top:-190px;</code> I could get this, but it is hard coding and not very responsive<br>
![image](https://github.com/user-attachments/assets/b0647e76-23b4-4cdb-bf92-6dca1ad489a1)

## Wednesday | 28-5-2025 | 20:06
`position: static | relative | absolute | fixed | sticky;`

`position:static;`: default value. Has no effect on the element.
 <br>`position: relative | absolute | fixed | sticky;`: With these values you can use the properties:
 1. `top`
 2. `bottom`
 3. `left`
 4. `right`
 5. `z-index`

`position:relative;`<br>
Using `top`, `left` will offset the element from it's initial top and left value. Pushing away the element from it's static position.<br>
<a href="https://codepen.io/Wassenaar/pen/qEddPEP" alt="demo position:relative;">Try demo on CodePen</a><br>
<img src="https://global.discourse-cdn.com/freecodecamp/original/4X/0/1/c/01ce1a46aa901418f35f666fffc5906c8f448beb.png" alt="example of an element with position:relative" width="500"><img src="https://global.discourse-cdn.com/freecodecamp/original/4X/a/9/0/a90cf2abdea69abd812f67df14f5c4572ee5e988.png" alt="example of an element with position:relative" width="500">


<hr>

`position:fixed;`<br>
Element is fixed on the page. You can place it in any position you like. In the demo you also learn about centering an element with the `translate`property.<br>
<a href="https://codepen.io/Wassenaar/pen/XJbbZoV" alt="demo position:relative;">Try demo on CodePen</a><br>
<img src="https://global.discourse-cdn.com/freecodecamp/original/4X/1/d/7/1d7b9cca1b78aee4c5e15813692c8476219f4e02.png" alt="demo of position:fixed;" width="1000">
