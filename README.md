# EXPERIMENT-06
# <p align="center"> FLEX-BOX </P>

## AIM: 
To create a web layout using flex-box
     
## ALGORITHM:

### STEP 1:
Set the display property to flex or inline-flex to establish it as a flex
container.
### STEP 2:
Specify the flex-direction property to determine the main axis direction. It can be set to row (default), row-reverse, column, or column-reverse.
### STEP 3:
Use the justify-content property to control the alignment of flex items along the main axis. It offers various values like flex-start, flex-end, center, space-between, space-around, and space-evenly.
### STEP 4:
Utilize the align-items property to define the alignment of flex items along the cross axis. It offers options such as flex-start, flex-end, center, baseline, and stretch.
### STEP 5:
Optionally, set the flex-wrap property to control how flex items wrap when they exceed the container's width. Values include nowrap (default), wrap, or wrap-reverse.
### STEP 6:
Use the flex-grow property to specify how flex items grow relative to each other if there is extra space along the main axis.
### STEP 7:
Utilize the flex-shrink property to determine how flex items shrink if there is insufficient space along the main axis.
### STEP 8:
Optionally, use the flex-basis property to set the initial size of flex items along the main axis.
### STEP 9:
Apply the order property to control the order in which flex items appear within the container. Lower values appear first.
•align-self: Overrides the align-items property for a specific flex item.
•	flex: Shorthand for setting flex-grow, flex-shrink, and flex-basis in one property.
•	align-content: Controls the alignment of multiple lines of flex items in case of multi-line flex containers.


## PROGRAM:

### index.html
```
<!DOCTYPE html>
<html lang="en">
<head>

<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" type="text/css" href="./assets/css/style.css">
<title>Flex_html</title>
</head>
<body>

<div class="header">
<div class="title">STORM<span>&reg;</span></div>
<div class="side">
<div class="h1"><hr /></div>
<div class="h2"><hr /></div>
</div>
</div>
<div class="mid">
<div class="left">
<div id="img1" width="800px"><img src="./assets/img/img1.png"/></div>
<div class="cont1">
OVERVIEW: WEATHER,<br />GLOBAL WARMING AND<br /> CLIMATE CHANGE
</div>
<div class="cont2">
"CLIMATE CHANGE" AND "GLOBAL WARMING"<br /> ARE OFTEN USED INTERCHANGEABLY BUT<br /> HAVE DISTINCT MEANINGS.
</div>
</div>
<div class="right">
<div id="img2"><img src="./assets/img/img2.png"/></div>
<div class="right-txt">THE WORLD IMPACT</div>
<div class="right-txt">TIME FOR CHANGE</div>
<div class="right-txt">SLOWING THE PROCESS</div>
</div>
</div>
</body>
</html>

```

### style.css
```css
/* body {
margin: 0;
padding: 0; display: flex;
flex-direction: column; align-items: center; justify-content: center; height: 100vh;
} */

@import url('https://fonts.googleapis.com/css2?family=Noto+Serif:ital@1&family=Poppins&display= swap');

*
{
font-family: 'Noto Serif', serif; font-family: 'Poppins', sans-serif; color: #F5F5F5;
}
body
{
margin: 0;
background-color: #101010; color: white;
font-family: 'Noto Serif', serif; font-family: 'Poppins', sans-serif;
}
.side
{
margin-top: 26px; margin-right: 10px; display: flex; width: 2rem; display: flex;
flex-direction: column;
}

body::-webkit-scrollbar
{
display: none;
}
 
.header
{
display: flex;
background-color: #000000; position: sticky;
top: 0;
z-index: 100;
justify-content: space-between; gap: 2rem;
}
.title
{
font-size: 5rem; display: flex;
}

.mid
{
display: flex; gap: 1.5rem; padding: 1rem;
}

.left
{
width: 60%; display: flex;
flex-direction: column;
}

#img1
{
height: 50vh; width: 100%;

}

.right
{
width: 40%; display: flex;
flex-direction: column;
}

#img2
{

height: 50vh; width: 100%;
 
}

.right-txt
{

display: flex; padding: 1.5rem;
border-bottom: 0.1px solid #F5F5F5;
}

.cont1
{
display: flex; font-size: 2.5rem;
justify-content: flex-start; margin: 0px;
}

.cont2
{
display: flex;
justify-content: flex-end; font-weight: 250;
color: gray;
}

``` 
  
## OUTPUT:

![image](https://github.com/Sugan2002/mern-FLEX-BOX-06/assets/77089743/b447c6d5-6472-4632-9c42-e9fae9448aa5)

## RESULT:

   Thus, the weblayout usinf flex-box is developed successfully using HTML & CSS.
