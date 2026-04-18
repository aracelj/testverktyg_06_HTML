# Veckouppgift 6  Web
By Araceli Jakobsson



## 1. What kind of HTML elements on the following:
### 1a. w3schools.com page
* w3schools page contains HTML for its web contents and CSS for its web design.

### 1b. wikipedia website on Thutmose II
*  It uses HTML for its web contents and CSS for its design.

### 1c. The correct arrangement of the codes found in https://davidsvson.github.io/parsonProblem/#/ND9TA5V911g2oDGBnQou
<header>
    <h1> Biblioteket ugglan </h1>
    <nav>
        <div> Välkommen </div>
        <div> Sök böcker </div>
        <div> Mina lån </div>
    </nav>
</header>
<main>
    <h2> Öppettider </h2>
    <p> Våra öppettider är: </p>
    <ul>
        <li> Måndag-fredag: 8-17 </li>
        <li> Lördag: 10-15 </li>
        <li> Söndag: 10-13 </li>
    </ul>
</main>

### 1d. Find as many errors as possible in the following HTML. Tips:
Original code:
<main>
<section>
<h1> Find the error
<p> This is an example of an HTML file. It contains several errors.
<img Let's show a nice image. />  
<p> Can you find them all? </p>
</p>   <!-- Not needed -->
</main>

* Below is the correct HTML:
<main>
  <section>
    <h1>Find the error</h1>

    <p>This is an example of an HTML file. It contains several errors.</p>

    <img src="image.jpg" alt="Let's show a nice image">

    <p>Can you find them all?</p>
  </section>
</main>


## 2. HTML Exercise
###1. Build a website for the library owl, which has the motto "wise as a book." Try to make the page as similar to the sketch as possible.
Tips:
<div class="row"> your buttons </div>
.row { display: flex; gap: 1em; flex-direction: row; }
```commandline
   owl_library/index.html
```


###1. Build a website that contains a recipe. The webpage should contains the ff:
1. Picture of the food
2. Heading - what is the name of the food
3. Short vignette, i.e. presentation of what is to be cooked
4. List of ingredients. Above the list there should be a subheading.
5. Instructions for how to cook the food. Remember to divide long text into several paragraphs. 
Start with a subheading, and feel free to add more sub-subheadings.

```commandline
    food_recipe/index.html
```

###3. Build a web page where you introduce yourself. The page should contain:
● headlines
● body text
● image
● at least one link to a relevant page
```commandline
    my_web/index.html
```