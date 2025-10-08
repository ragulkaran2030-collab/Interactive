# Ex.08 Design of Interactive Image Gallery
## Date:8.10.2025

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Gallery</title>
    <link rel="stylesheet" href="./style.css">
</head>
<body>
    <header>
        <h1>Anime Image Gallery</h1>
    </header>

    <main>
        <section class="screen">
           <img class="box" src="./assets/img01.png" alt="">
           <img class="box" src="./assets/img02.png" alt="">
           <img class="box" src="./assets/img03.png" alt="">
           <img class="box" src="./assets/img04.png" alt="">
           <img class="box" src="./assets/img05.png" alt="">
           <img class="box" src="./assets/img06.png" alt="">
           <img class="box" src="./assets/img07.png" alt="">
           <img class="box" src="./assets/img08.png" alt="">
        </section>
    </main>

</body>
</html>

style.css
body {
  height: 100vh;
}

header {
  text-align: center;
  margin-bottom: 3rem;
}

.screen {
  min-height: 100vh;
  display: flex;
  gap: 2rem;
  flex-wrap: wrap;
  justify-content: center;
}

.box {
  height: 200px;
  width: 200px;
  background-color: peru;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
```




## OUTPUT:
![alt text](<Screenshot 2025-10-08 131825.png>)
## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
