# Teaching kids programming through games development with HTML / CSS / JS

This course is intended for kids 8+ years old that with help of their parents will learn how to program interactive browser games with CSS, HTML and JavaScript. It's recommended to check [code monkey](https://www.playcodemonkey.com/) and [scratch](https://scratch.mit.edu/) project before taking this course.

## Credits
- [Freepik Cats Collection Images](https://www.freepik.com/free-vector/coloured-cats-collection_1072063.htm) 

## Tools
- [Visual Studio Code Editor](https://code.visualstudio.com/) - free, open source, cross platform

## Lesson 1
![Lesson 1](https://raw.githubusercontent.com/1rosehip/coding-games-for-kids-to-learn-programming/master/lesson-1/lesson-1.png "Lesson 1")

In this lesson we are going to create a game stage and study about basic HTML and CSS definitions.
    
### Parent
- create a new folder called **lesson-1** and copy all content from [here](https://github.com/1rosehip/coding-games-for-kids-to-learn-programming/tree/master/lesson-1)
- Open **Visual Studio Code** -> File -> Open -> select **lesson-1** folder
- Open **index.html** file in editor 
- Right click -> View in browser    
- Tell the child about definitions of HTML and CSS, what is DIV (small unit, block), what is class (style, color, look).
- Tell about 3 colors that can be changed in the styles: border, text and background color.
- Tell about width and height of the DIV.

### Kid Tasks
- Change the colors using **color picker** so border will be red, background yellow and text blue
- Change the colors using **color picker** so border will be blue, background black and text white
and text blue
- Change the colors using **color picker** so border will be green, background pink and text black
- Change width and height to be very small (10px, 5px, 20px)
- Change width and height to be very large (1000px, 2000px, 300px)
- Change width to be as page width
- Change height to be as page height
- Change game title and its color to the favorite kid's game name and color
- Ask the kids to create a game stage with colors and width / height as they want
- Ask kid to create multiple DIVs if different colors and sizes.

## Lesson 2
![Lesson 2](https://raw.githubusercontent.com/1rosehip/coding-games-for-kids-to-learn-programming/master/lesson-2/lesson-2.png "Lesson 2")

In this lesson we are going to add a person to our game stage.

### Kid Tasks
- Create a DIV inside the game stage
- Add it a class **person**
- Go to css and copy all styles from **.game-1**
- Change width and height to be 30px
- Change border and background colors as kid wants

### Parent
- Tell the kid about absolute position and top / left / right / bottom properties
- Add top: 10px; left: 40px; position: absolute; to CSS

### Kid Tasks
- Move the person to the right top corner
- Move the person to the right bottom corner
- Move the person to the left bottom corner
- Move the person to tht left top corner
- Move the person to the center  

## Lesson 3

![Lesson 3](https://raw.githubusercontent.com/1rosehip/coding-games-for-kids-to-learn-programming/master/lesson-3/lesson-3.png?v=1 "Lesson 3")

In this lesson we are going to add an image for the game person.

### Parent
- Tell the kid about the [img tag](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img) and add with the kid an image located [here](https://github.com/1rosehip/coding-games-for-kids-to-learn-programming/tree/master/img/cats) to the person's DIV.
- Set image width to be 100px.
- Refer to **lesson-3/index.html** folder as reference.

### Kid Tasks
- Ask the kid to change width and height of the person DIV to be big enough to contain the cat image.
- Ask the kid to draw his / her own person in the favorite graphic editor and insert instead of the cat.
- Remove the container DIV and add its classes to the image using class **cat**. Try to remove different styles and check how it influences the stage.

## Lesson 4

![Lesson 4](https://raw.githubusercontent.com/1rosehip/coding-games-for-kids-to-learn-programming/master/lesson-4/lesson-4.png "Lesson 4")

In this lesson we are going to add some basic JavaScript to the stage.

### Parent
- Tell the kid about the JavaScript (can change HTML dynamically). Shot him / her tag SCRIPT in HTML.
- Open [main.js](https://github.com/1rosehip/coding-games-for-kids-to-learn-programming/blob/master/lesson-4/main.js) that is located at **lesson-4** folder. Tell the kid about **console.log**. Show him / her google developer toolbar.

### Kid Tasks
- Kid should change console.log text and find it in google developer toolbar.
- Add another console logs.

### Parent
- Tell the kid about [HTML document](https://developer.mozilla.org/en-US/docs/Web/API/Document)
- Add to the JS **console.log(document);** and show it to the kid in the console.
- Tell that every HTML element may have a [unique id](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/id).
- Add **id="my-cat"** to the cat image.
- Add **console.log(document.getElementById('my-cat'));** to the JavaScript and show the kid image object in the console

### Kid Tasks
- Get a new cat image from [here](https://github.com/1rosehip/coding-games-for-kids-to-learn-programming/tree/master/img/cats) or draw your own image.
- Add this image to HTML using **img** tag.
- Add a unique **id** to this image. Select any name you want using small English letters, numbers and dashes without spaces.
- Add javascript that prints this image object to console using **document.getElementById**

## Lesson 5

![Lesson 5](https://raw.githubusercontent.com/1rosehip/coding-games-for-kids-to-learn-programming/master/lesson-5/lesson-5.png "Lesson 5")

In this lesson we are going to learn about variables and how to use them.

### Parent
- Tell about variables in javascript and their usage.
- Tell about [let](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/let) and [const](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/const) and what is the difference
- Get image cat object from the previous lesson and save it as const variable. Please refer to [main.js](https://github.com/1rosehip/coding-games-for-kids-to-learn-programming/blob/master/lesson-5/main.js) if needed.

### Kid Tasks
- Create a new **const** variable and put there any number. Print it in the console.
- Create a new **const** variable and put there any text. Print it in the console.
- Create a new variable named **num2** using **let**. Put there 10. 
- Add 1 to this variable using the following code: **num2 = num2 + 1;**
- Print **num2** and check the result value
- Try other arithmetic operations like -, * and /.

## Lesson 6

Let's add some action!

### Parent
- Tell the kid about [alert](https://developer.mozilla.org/en-US/docs/Web/API/Window/alert) popup.
- Add **alert('I like JavaScript!!!');** to the JS and show the kid the result popup.

### Kid Tasks
- Ask from kid to change the popup text to something else.
- Ask from kid to create his / her own alert popups.

### Parent
- Tell about [events](https://en.wikipedia.org/wiki/Event_(computing)). Give event examples (mouse click, keyboard events, touch events etc.)
- Let's add **onclick** event listener to our JS. Move alert statement to its body. Please refer to [main.js](https://github.com/1rosehip/coding-games-for-kids-to-learn-programming/blob/master/lesson-6/main.js) for example.
- Ask from kid to click on the image and see the result.

### Kid Tasks
- Change the alert text to something else.
- Get a new cat image from [here](https://github.com/1rosehip/coding-games-for-kids-to-learn-programming/tree/master/img/cats) or draw your own image.
- Add this image to HTML using **img** tag.
- Add a unique **id** to this image. Select any name you want using small English letters, numbers and dashes without spaces.
- Get this new image by id using **document.getElementById** and save it in the **const** variable.
- Copy **addEventListener** from another example and make it show the popup with some text on image click!